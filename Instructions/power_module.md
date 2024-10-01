## Montagem do Módulo de Energia
![power_module_assembly_front](Photos/power_module_assembly_front.jpg)

### Ferramentas
- Conjunto de Chaves Balldriver, Padrão
- Conjunto de Chaves Balldriver, Métrico
- Conjunto de Chaves de Porca, Padrão
- Conjunto de Chaves de Porca, Métrico
- Cortadores de Fio
- Alicates
- Chave de Fenda Phillips

### Instruções
1. Reúna todos os materiais para esta submontagem conforme mostrado: ![power_module_materials](Photos/power_module_materials.jpg)
2. **POR FAVOR LEIA, ISTO É MUITO IMPORTANTE: Defina a fonte de alimentação de 12V para 115V ou 230V, dependendo de onde você mora. Se você não fizer isso corretamente, isso danificará a fonte e tornará inutilizável.**
3. Insira 2 dos **Fusíveis de Vidro** (ELC-FUS-0001) no **Módulo de Entrada de Energia** (ELC-PEM-0001) conforme mostrado: ![power_module_power_entry_fuse](Photos/power_module_power_entry_fuse.jpg)
4. Insira o **Módulo de Entrada de Energia Fusível** e o **Interruptor de Energia** (ELC-SWI-0001) no **Grande Suporte da Fonte de Alimentação** (STR-PNL-0002) conforme mostrado. **IMPORTANTE: Certifique-se de ter a orientação correta, pois é muito difícil retirá-los após inseridos** ![power_module_inserted_switch_power_entry](Photos/power_module_inserted_switch_power_entry.jpg)
5. Monte o **Relé Temporizador Programável Multifuncional** (ELC-REL-0002) em um dos **Pequenos Suportes da Fonte de Alimentação** (STR-PNL-0003) com 4 parafusos **S-#04-40-025-BTN-S-SS (Saco 13)** (parafusos de cabeça redonda de 4-40 x 0,25"), 4 espaçadores de alumínio **S-#04-40-025-STD-H-AL-MF (Saco 17)** (4-40 x 0,25", espaçador de alumínio macho-fêmea, 0,1875" de comprimento) e 4 porcas **S-#04-40-094-NUT-H-SS (Saco 15)** (4-40) conforme mostrado: ![power_module_relay_mount](Photos/power_module_relay_mount.jpg)
6. Monte os **Pequenos Suportes da Fonte de Alimentação** no **Grande Suporte da Fonte de Alimentação** com 4 parafusos **S-#08-32-025-BTN-S-SS (Saco 1)** (parafusos de cabeça redonda de 8-32 x 0,25") e 4 porcas **S-#08-32-094-NUT-H-SS (Saco 6)** (8-32) conforme mostrado: ![power_module_brackets](Photos/power_module_brackets.jpg)
7. Monte a **Fonte de Alimentação de 24V** (PWR-SUP-0001) nos **Suportes da Fonte de Alimentação Montados** com 2 parafusos **M-004-07-014-BTN-S-SS (Saco 29)** (parafusos de cabeça redonda de M4 x 14mm) e 2 parafusos **M-004-07-005-BTN-S-SS (Saco 28)** (M4 x 5mm) conforme mostrado: ![power_module_24v](Photos/power_module_24v.jpg)
8. Conecte o **Carregamento do Módulo de Entrada de Energia** ao **Posição 1A do Interruptor de Energia** e ao **COM do Relé Multifuncional** com **Terminal de Conexão Rápida Fêmea de 6,35 mm para 10-12 AWG com Fio Preto de 432 mm e Fio Preto de 76 mm para Terminal de Conexão Rápida Fêmea de 3,96 mm para 14-16 AWG** (WIR-HAR-0026) conforme mostrado: ![power_module_load](Photos/power_module_load.jpg)
9. Conecte **Posição 2A do Interruptor de Energia**, **Posição 3A do Interruptor de Energia** e **NO do Relé Multifuncional** com **Terminal de Conexão Rápida Fêmea Duplo de 6,35 mm para 10-12 AWG com Fios Pretos de 432 mm, 533 mm e 533 mm com Fio Preto de 51 mm Conectando Terminais** (WIR-HAR-0027). Certifique-se de que a orientação tenha os dois fios pretos não conectados com comprimento aproximadamente igual. Veja abaixo: ![power_module_switched_load_initial](Photos/power_module_switched_load_initial.jpg)
10. Conecte o **Terminal de Conexão Rápida Fêmea de 6,35 mm para 10-12 AWG com Dois Fios Brancos de 457 mm** (WIR-HAR-0024) ao **Neutro (N) do Módulo de Entrada de Energia**
11. Conecte **Terminal de Conexão Rápida Fêmea Duplo de 6,35 mm para 10-12 AWG a Dois Fios Verdes de 483 mm Conectados por Fio Verde de 114 mm** (WIR-HAR-0025) ao **Terra do Módulo de Entrada de Energia** e **Posição 6B do Interruptor de Energia**
12. Conecte **Plugue Molex SR de 4 Posições com Etiqueta "RPI GPIO 11/13/15/17" com Fios de Comprimento Variado** (WIR-HAR-0034) fio vermelho ao **Posição 4B do Interruptor de Energia** e fio amarelo ao **Posição 5B do Interruptor de Energia**. As conexões para o interruptor de energia e o módulo de entrada de energia devem ficar assim: ![power_module_connected_power_entry_and_switch](Photos/power_module_connected_power_entry_and_switch.jpg)
13. Agrupe os fios conectados ao **Módulo de Entrada de Energia** e ao **Interruptor de Energia** e prenda-os com uma abraçadeira na parte inferior do **Módulo de Entrada de Energia**
14. Envolva todo o **Módulo de Entrada de Energia** e o **Interruptor de Energia** com Fita Isolante conforme mostrado: ![power_module_taped_power_entry_and_switch](Photos/power_module_taped_power_entry_and_switch.jpg)
15. Conecte os fios verdes aos terminais de terra de cada fonte de alimentação
16. Conecte os fios pretos às cargas (L) de cada fonte de alimentação
17. Conecte os fios brancos aos normais (N) de cada fonte de alimentação
18. Conecte o chicote de fios rotulado 24V à fonte de alimentação de 24V (preto no -V e vermelho no +V)
19. Conecte os chicotes de fios rotulados 12V@1, 12V@2, 12V@3, 12V@4 e os chicotes de fios individuais vermelho e preto à fonte de alimentação de 12V (certifique-se de colocar apenas até 2 fios por terminal)
20. Conecte o fio branco 24 AWG (o mais fino) no CH1 no relé multifuncional
21. Certifique-se de que há fita ao redor da extremidade do fio amarelo 24 AWG e prenda-o próximo ao relé multifuncional.
22. Agrupe os fios nas bordas (todos os fios conectados à fonte de 12V em uma borda, todos os fios conectados à fonte de 24V em outra borda, as tomadas em outra borda). A montagem deve ficar assim: ![power_module_pre_routing](Photos/power_module_pre_routing.jpg)
23. Agrupe a principal veia de fios e prenda-os com uma abraçadeira conforme mostrado: ![power_module_main_vein_inside](Photos/power_module_main_vein_inside.jpg) ![power_module_main_vein_outside](Photos/power_module_main_vein_outside.jpg)
24. Feche a zona de roteamento montando a fonte de alimentação de 12V nos suportes da fonte de alimentação. Use 8 parafusos **M-004-07-005-BTN-S-SS (Saco 28)** (parafusos de cabeça redonda de M4 x 5mm). A montagem final deve ficar assim: ![power_module_assembly_front](Photos/power_module_assembly_front.jpg) ![power_module_assembly_bottom](Photos/power_module_assembly_bottom.jpg)

