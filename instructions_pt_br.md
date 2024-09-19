# Instruções de Montagem do PFC2

![pfc2](Instructions/Photos/pfc2.jpg)

## Antes de começar:
Imprimir a [Lista de Materiais (BOM)](./BOM/BOM_MASTER.xlsx) é útil como referência. As descrições contidas nela ajudam a distinguir entre as peças.
Baixe os documentos CAD [aqui](CAD/GrabCAD) para serem visualizados no e-drawings-viewer.

## Instruções de Montagem dos Submódulos
Siga as instruções para montar cada submódulo. Cada submódulo pode ser montado em paralelo, mas alguns levarão mais tempo que outros para serem concluídos.

- [Estrutura](./Instructions/frame.md)
- [Painel Eletrônico](./Instructions/electronics_panel.md)
- [Módulo de Controle](./Instructions/brain_module.md)
- [Painel de Luz](./Instructions/light_panel.md)
- [Módulo de Energia](./Instructions/power_module.md)
- [Coletor de Água](./Instructions/water_manifold.md)
- [Resfriador](./Instructions/chiller.md)

## Configurar os Componentes Elétricos nos Modos Adequados
1. Configure o **Relé Multifuncional** no **Modo 10** e o **Timer 1** para 20 segundos
1. Ajuste o **Gerador de Pulso** para **140Hz**
1. Configure os **Circuitos Atlas** no **Modo I2C**
1. Na **Placa de Sinal**, isole os pontos de solda abaixo de ambos os conectores BNC e cubra com fita isolante ou fita kapton

## Montagem do Painel Eletrônico
1. Coloque o painel eletrônico na estrutura parcialmente montada, conforme mostrado.<!-- TODO: Não mostrado --> Fixe-o frouxamente no lugar com alguns postes de encadernação **S-018-32-075-PST-F-AL(Bag 31)** ao longo de cada lado.

## Montar os Componentes Laterais da Câmara no Painel Eletrônico
1. O painel está montado e o isolamento está no lugar:
1. Monte o Módulo de Controle de Temperatura, a saída de ar e a bomba de aeração em suas respectivas zonas no painel eletrônico.

## Montagem da Seção Superior da Estrutura
1. Monte a seção superior da estrutura. Alinhe os conectores apropriados da estrutura, batendo gradualmente em cada conector com pequenos golpes.

## Montar o Conjunto de Fonte de Alimentação
1. Monte o Conjunto de Fonte de Alimentação no topo da caixa elétrica usando três parafusos **S-025-20-438-BTN-S-SS (Bag 26)** 1/4-20.
1. Conecte os fios da fonte de alimentação nos locais apropriados no coletor de controle.

## Montagem dos Painéis do Corpo
1. Monte o restante dos painéis do corpo. Ao alinhar para a montagem, observe as pequenas marcações gravadas indicando a orientação do painel. Cada uma dessas marcações está voltada para dentro, possui uma seta e uma palavra para mostrar a orientação, e a maioria se alinha com a marcação de um painel adjacente.

## Integração Final
- Consulte o modelo CAD para a integração final e assista ao [vídeo de montagem](https://youtu.be/Uf1FqjcPWsI)!

## Notas de Integração Final
- Ao instalar o sensor de temperatura e umidade do ar, envolva um pedaço de fita isolante ao redor da base para que ele se encaixe firmemente no suporte.
