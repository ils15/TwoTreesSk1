# Two Trees SK1 3D Printer Repository | Repositório da Impressora 3D Two Trees SK1

<div align="center">
  <img src="https://oss.twotrees3d.com/3DPrinterSeries/SK1/8.0en.png" alt="Two Trees SK1 3D Printer" width="600"/>
</div>

<details open>
<summary><b>English Version</b></summary>

This repository provides detailed resources, configurations, and guides for the **Two Trees SK1 3D Printer**, a CoreXY-based machine designed for high-speed printing. The goal is to assist users in setting up, troubleshooting, and optimizing their printers effectively.

## Features of the Two Trees SK1

- **CoreXY Structure**: Stable and precise motion system for high-quality prints.
- **Print Volume**: 256 × 256 × 256 mm (10" x 10" x 10").
- **High-Speed Printing**: Up to 700 mm/s with accelerations up to 20,000 mm/s² (recommended: 300 mm/s for everyday printing).
- **Hotend & Extruder**:
  - All-metal hotend supporting up to 300°C for wider material compatibility.
  - Dual Gear Direct Drive Extruder with a gear ratio of 9.5:1 for precise filament control.
- **Bed Leveling**: Automatic Z-Tilt leveling with three independent Z-motors for perfect first layers.
- **Build Surface**: PEI-coated spring steel sheet for excellent adhesion and easy part removal.
- **Electronics**:
  - Silent TMC2209 stepper drivers with sensorless homing capability.
  - STM32F4 32-bit controller board with high processing power.
- **Connectivity**: USB, Ethernet, Wi-Fi for flexible printing options.
- **User Interface**: 4.3-inch color touchscreen plus web interface when running Klipper.
- **Additional Features**:
  - Filament run-out detection with automatic print pause.
  - Power loss recovery function.
  - Open-source Klipper firmware for advanced motion planning and customization.
- **Optional Add-ons**: AI camera for print monitoring, enclosure for temperature-sensitive materials.

## Repository Structure

### **1. Klipper**
Contains Klipper firmware configurations and macros for advanced users:
- Installation guides for Klipper firmware.
- Customizable `printer.cfg` files with optimized settings.
- Pre-configured macros for common tasks and print sequences.
- Sanity check scripts to ensure proper printer operation.

### **2. Board**
Includes hardware-related resources:
- Wiring diagrams and schematics for the mainboard.
- Technical specifications of the electronics.
- Pin assignments and connector details.

### **3. Originais TT**
Original files provided by Two Trees:
- Stock firmware and factory configurations.
- Official user manuals and assembly guides.
- Warranty information and support documentation.

### **4. User Manual**
Comprehensive guides for operating your printer:
- Setup and first-time configuration
- Maintenance procedures and schedules
- Advanced tuning techniques
- Troubleshooting guides with illustrated solutions

### Planned Additions
Future updates will include:
- Optimized slicer profiles for PrusaSlicer, Cura, and SuperSlicer.
- Calibration models with step-by-step tuning workflows.
- Troubleshooting flowcharts for common issues.
- Hardware modification guides and printable upgrade parts.

## Getting Started

### Assembly
1. Follow the assembly instructions in the [official manual](https://wiki.twotrees3d.com/en/3DPrinterSeries/SK1) or included PDF files in the repository.
2. Double-check all belts for proper tension and ensure frame squareness.
3. Install optional components such as Wi-Fi antennas or enclosures if needed.

### Firmware Setup
1. Use the stock firmware or install Klipper for advanced features.
2. For Klipper:
   - Refer to the `Klipper` folder for installation steps and configuration files.
   - Update via SSH using pre-installed tools like KIAUH if necessary.
   - Run our configuration verification scripts to confirm proper setup.

### Slicer Configuration
1. Set up your slicer using recommended profiles from the repository.
2. Adjust print settings based on:
   - Material type (PLA, PETG, ABS, etc.)
   - Desired print quality vs. speed
   - Part mechanical requirements

### Test Prints
Run test prints to verify proper setup:
1. Start with a simple calibration cube to check dimensional accuracy.
2. Print a temperature tower to find optimal settings for your filament.
3. Try a speed test model to determine maximum reliable printing speeds.
4. Complete a benchmark model to validate overall printer performance.

## Troubleshooting

### Common Issues and Solutions

#### Mechanical Issues
- **Layer Shifting**: Check belt tension, pulley alignment, and current settings.
- **Z-Banding**: Ensure Z-axis screws are clean and properly lubricated.
- **Uneven First Layer**: Re-run Z-tilt calibration and adjust Z-offset.

#### Electrical Issues
- **Stepper Motor Noise**: Verify TMC driver settings and wiring connections.
- **Heating Problems**: Check thermistor connections and PID tuning.
- **Communication Errors**: Inspect USB cables and network configurations.

#### Software Issues
- **Slicer Problems**: Validate settings match printer capabilities.
- **Firmware Glitches**: Update to the latest stable release.
- **Connectivity Issues**: Check IP settings and firewall configurations.

## Contributing

We welcome contributions to improve this repository! You can:
- Submit pull requests with enhanced configurations or tested modifications.
- Report issues or suggest improvements in documentation.
- Share your successful print profiles and calibration results.
- Translate documentation to additional languages.

## Additional Resources

### Official Links
- [Product Page](https://br.twotrees3dofficial.com/products/sk1-corexy-3d-printer-twotrees)
- [Official Wiki](https://wiki.twotrees3d.com/en/3DPrinterSeries/SK1)

### Community Resources
- [Reddit r/TwoTrees](https://www.reddit.com/r/TwoTrees/)
- [Grupo do Facebook: Two Trees SK1 Owners](https://www.facebook.com/groups/1699130501014653)

### Reviews & Guides
For more insights into the SK1's performance and potential upgrades:
- [Tom's Hardware Review](https://www.tomshardware.com/3d-printing/two-trees-sk1-review)
- [3DWithUs Review](https://3dwithus.com/two-trees-sk1-review-3d-printer-testing)
- [Teaching Tech Calibration Guide](https://teachingtechyt.github.io/calibration.html) (General 3D printer calibration)

---
</details>

<details>
<summary><b>Versão em Português</b></summary>

Este repositório fornece recursos detalhados, configurações e guias para a **Impressora 3D Two Trees SK1**, uma máquina baseada em cinemática CoreXY projetada para impressão em alta velocidade. O objetivo é ajudar os usuários na configuração, solução de problemas e otimização de suas impressoras de forma eficaz.

## Características da Two Trees SK1

- **Estrutura CoreXY**: Sistema de movimento estável e preciso para impressões de alta qualidade.
- **Volume de Impressão**: 256 × 256 × 256 mm (10" x 10" x 10').
- **Impressão de Alta Velocidade**: Até 700 mm/s com acelerações de até 20.000 mm/s² (recomendado: 300 mm/s para impressão diária).
- **Hotend e Extrusora**:
  - Hotend totalmente metálico suportando até 300°C para maior compatibilidade de materiais.
  - Extrusora Direct Drive de Engrenagem Dupla com relação de engrenagens de 9.5:1 para controle preciso do filamento.
- **Nivelamento da Mesa**: Nivelamento automático Z-Tilt com três motores Z independentes para camadas iniciais perfeitas.
- **Superfície de Impressão**: Chapa de aço flexível revestida com PEI para excelente adesão e fácil remoção das peças.
- **Eletrônica**:
  - Drivers de motor TMC2209 silenciosos com capacidade de homing sem sensores.
  - Placa controladora STM32F4 de 32 bits com alto poder de processamento.
- **Conectividade**: USB, Ethernet, Wi-Fi para opções flexíveis de impressão.
- **Interface de Usuário**: Tela colorida touchscreen de 4,3 polegadas e interface web quando rodando Klipper.
- **Recursos Adicionais**:
  - Detecção de fim de filamento com pausa automática de impressão.
  - Função de recuperação após queda de energia.
  - Firmware Klipper de código aberto para planejamento de movimento avançado e personalização.
- **Complementos Opcionais**: Câmera com IA para monitoramento de impressão, gabinete para materiais sensíveis à temperatura.

## Estrutura do Repositório

### **1. Klipper**
Contém configurações de firmware Klipper e macros para usuários avançados:
- Guias de instalação do firmware Klipper.
- Arquivos `printer.cfg` personalizáveis com configurações otimizadas.
- Macros pré-configuradas para tarefas comuns e sequências de impressão.
- Scripts de verificação de sanidade para garantir o funcionamento adequado da impressora.

### **2. Board**
Inclui recursos relacionados ao hardware:
- Diagramas de fiação e esquemáticos da placa principal.
- Especificações técnicas da eletrônica.
- Atribuições de pinos e detalhes dos conectores.

### **3. Originais TT**
Arquivos originais fornecidos pela Two Trees:
- Firmware original e configurações de fábrica.
- Manuais oficiais do usuário e guias de montagem.
- Informações de garantia e documentação de suporte.

### **4. Manual do Usuário**
Guias abrangentes para a operação da sua impressora:
- Configuração inicial e primeira utilização
- Procedimentos e cronogramas de manutenção
- Técnicas de ajuste avançadas
- Guias de solução de problemas com soluções ilustradas

### Adições Planejadas
Atualizações futuras incluirão:
- Perfis de fatiador otimizados para PrusaSlicer, Cura e SuperSlicer.
- Modelos de calibração com fluxos de trabalho detalhados para ajuste fino.
- Fluxogramas de solução de problemas para questões comuns.
- Guias de modificação de hardware e peças de atualização imprimíveis.

## Começando

### Montagem
1. Siga as instruções de montagem no [manual oficial](https://wiki.twotrees3d.com/en/3DPrinterSeries/SK1) ou nos arquivos PDF incluídos no repositório.
2. Verifique novamente todas as correias quanto à tensão adequada e garanta o esquadro do quadro.
3. Instale componentes opcionais como antenas Wi-Fi ou gabinete, se necessário.

### Configuração do Firmware
1. Use o firmware original ou instale o Klipper para recursos avançados.
2. Para o Klipper:
   - Consulte a pasta `Klipper` para etapas de instalação e arquivos de configuração.
   - Atualize via SSH usando ferramentas pré-instaladas como KIAUH, se necessário.
   - Execute nossos scripts de verificação de configuração para confirmar a configuração adequada.

### Configuração do Fatiador
1. Configure seu fatiador usando perfis recomendados do repositório.
2. Ajuste as configurações de impressão com base em:
   - Tipo de material (PLA, PETG, ABS, etc.)
   - Qualidade de impressão desejada vs. velocidade
   - Requisitos mecânicos da peça

### Impressões de Teste
Execute impressões de teste para verificar a configuração adequada:
1. Comece com um cubo de calibração simples para verificar a precisão dimensional.
2. Imprima uma torre de temperatura para encontrar configurações ideais para seu filamento.
3. Teste um modelo de velocidade para determinar as velocidades máximas confiáveis de impressão.
4. Complete um modelo de benchmark para validar o desempenho geral da impressora.

## Solução de Problemas

### Problemas Comuns e Soluções

#### Problemas Mecânicos
- **Deslocamento de Camada**: Verifique a tensão da correia, alinhamento da polia e configurações de corrente.
- **Marcas de Z (Z-Banding)**: Garanta que os parafusos do eixo Z estejam limpos e adequadamente lubrificados.
- **Primeira Camada Irregular**: Execute novamente a calibração Z-tilt e ajuste o Z-offset.

#### Problemas Elétricos
- **Ruído do Motor de Passo**: Verifique as configurações do driver TMC e conexões de fiação.
- **Problemas de Aquecimento**: Verifique as conexões do termistor e o ajuste PID.
- **Erros de Comunicação**: Inspecione os cabos USB e configurações de rede.

#### Problemas de Software
- **Problemas do Fatiador**: Valide se as configurações correspondem às capacidades da impressora.
- **Falhas de Firmware**: Atualize para a versão estável mais recente.
- **Problemas de Conectividade**: Verifique as configurações de IP e configurações de firewall.

## Contribuindo

Nós damos as boas-vindas a contribuições para melhorar este repositório! Você pode:
- Enviar pull requests com configurações aprimoradas ou modificações testadas.
- Relatar problemas ou sugerir melhorias na documentação.
- Compartilhar seus perfis de impressão bem-sucedidos e resultados de calibração.
- Traduzir documentação para idiomas adicionais.

## Recursos Adicionais

### Links Oficiais
- [Página do Produto](https://br.twotrees3dofficial.com/products/sk1-corexy-3d-printer-twotrees)
- [Wiki Oficial](https://wiki.twotrees3d.com/en/3DPrinterSeries/SK1)

### Recursos da Comunidade
- [Reddit r/TwoTrees](https://www.reddit.com/r/TwoTrees/)
- [Grupo do Facebook: Two Trees SK1 Owners](https://www.facebook.com/groups/1699130501014653)

### Análises e Guias
Para mais insights sobre o desempenho da SK1 e possíveis atualizações:
- [Análise do Tom's Hardware](https://www.tomshardware.com/3d-printing/two-trees-sk1-review)
- [Análise do 3DWithUs](https://3dwithus.com/two-trees-sk1-review-3d-printer-testing)
- [Guia de Calibração do Teaching Tech](https://teachingtechyt.github.io/calibration.html) (Calibração geral de impressoras 3D)

</details>

By leveraging its robust hardware and open-source firmware, the Two Trees SK1 can be a powerful tool when properly configured. This repository aims to help users unlock its full potential!

