# Embarcados-Filtros
Processamento de Imagem com filtros Gradiente/ Passa Alta/ Passa Baixa

;-----------------------------------------------------------------------------------;
;Descrição:                                                                         ;
;       Deseja-se implementar um jogo de Ping Pong                                  ;
;                                                                                   ; 
;       Regras:                                                                     ;    
;                                                                                   ;    
;       1) Tamanho da Raquete deve ser uma reta de 50 pixels.                       ;
;       2) Movimentaçãoda bolinha apenas na vertical e com as teclas “u” e “d”      ;
;          para deslocar a raquete para cima e para baixo.                          ;                                
;       4) Velocidade da bolinha deve ser controlada pelas teclas “+” e “-“,        ;
;          do teclado numérico.                                                     ;
;       5) Cor da bola deve ser vermelha.                                           ;                    
;       6) Todas as vezes em que o jogador consegue rebater a bola,                 ;
;          deve-se adicionar 1 ponto ao placar do jogador.                          ;
;       7) Caso o jogador não consiga rebater a bola e ela se choca com a lateral   ;  
;          direita da tela, deve-se adicionar 1 ponto ao placar do computador.      ;
;       8) Implemente um placar de dois dígitos para contabilizar a pontuação.      ;
;       9) Para sair do jogo, deve-se pressionar a tecla “Esc”.                     ;
;       10) O fundo de tela deve ser na cor preta e as linhas na cor branca.        ;
;       11) Toda a leitura de teclas deve ser feita, por interrupção de hardware,   ;
;           tomando-se como base o programa “tecbuf.asm”                            ;
;       12) Deve ser implementado 5 diferentes velocidades da bolinha.              ;
;       13)O jogo deve ser iniciado na velocidade mais baixa.                       ;
;                                                                                  	; 
;       Tabela 1:         Tabela de Cores modo VGA 640×480                          ;
;                            Preto 0    ~   Cinza 8                                 ;
;                            Azul 1     ~   Azul_claro 9                            ;
;                            Verde 2    ~   Verde_claro 10                          ;
;                            Cyan 3     ~   Cyan_claro 11                           ;
;                            Vermelho 4 ~   Rosa 12                                 ;
;                            Magenta 5  ~   Magenta_claro 13                        ;
;                            Marrom 6   ~   Amarelo 14                              ;
;                            Branco 7   ~   Branco_intenso 15                       ;
;                                                                                   ;
;                                                                                   ;
;-----------------------------------------------------------------------------------;
