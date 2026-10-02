# 📘 Manual Técnico

## 📋 Sumário

- [NR-17 — Ergonomia](#nr-17--ergonomia)
- [Descarga Eletrostática (ESD)](#descarga-eletrostática-esd)
- [Tipos de Danos aos Componentes](#tipos-de-danos-aos-componentes)
- [Comparativo de Sensibilidade à ESD](#comparativo-de-sensibilidade-à-esd)
- [Prevenção contra ESD](#prevenção-contra-esd)
- [Sustentabilidade e E-lixo](#sustentabilidade-e-e-lixo)
- [Responsabilidade Socioambiental](#responsabilidade-socioambiental)
- [Logística Reversa em Manaus](#logística-reversa-em-manaus)
- [Cuidados no Manuseio de Hardware](#cuidados-no-manuseio-de-hardware)
- [Alertas de ESD e Energia](#alertas-de-esd-e-energia)
- [Checklist do Técnico](#checklist-do-técnico)

---

# NR-17 — Ergonomia

A **NR-17** é uma Norma Regulamentadora do Ministério do Trabalho e Emprego que estabelece diretrizes para adaptar as condições de trabalho às características psicofisiológicas dos trabalhadores, buscando garantir **conforto, segurança e saúde**.

## O que a NR-17 exige na prática?

- **Mobiliário e equipamentos:** mesas, cadeiras e suportes ajustáveis para evitar posturas inadequadas e fadiga muscular.
- **Conforto ambiental:** controle de iluminação, ruído, umidade e temperatura.
- **Organização do trabalho:** ritmo adequado, pausas regulares e gestão da carga mental.
- **Levantamento de peso:** limites seguros para transporte e descarga manual de materiais.
- **Avaliações:** AEP (Avaliação Ergonômica Preliminar) e, quando necessária, AET (Análise Ergonômica do Trabalho).

## Importância para a saúde

A aplicação da NR-17 contribui para prevenir:

- LER/DORT;
- Dores crônicas na coluna;
- Estresse;
- Fadiga mental.

---

# ⚡ Descarga Eletrostática (ESD)

A **Descarga Eletrostática (ESD)** é o fluxo repentino e momentâneo de corrente elétrica entre dois objetos com potenciais elétricos diferentes.

Na eletrônica, a eletricidade estática acumulada no corpo humano pode causar falhas e danos em componentes semicondutores.

## Como a carga se acumula?

O corpo humano pode acumular cargas pelo **efeito triboelétrico**, causado pelo atrito entre materiais.

O manual apresenta valores que podem variar de **500 V a mais de 15.000 V**.

Como o limiar de percepção humana para um choque estático é de aproximadamente **3.000 V**, uma descarga prejudicial pode ocorrer sem ser percebida.

---

# 🔥 Tipos de Danos aos Componentes

Quando uma descarga ESD atinge componentes como RAM, Flash, CPU, GPU e placa-mãe, podem ocorrer dois tipos principais de danos.

## 1. Dano imediato — falha catastrófica

A descarga pode destruir instantaneamente estruturas internas do semicondutor.

### Possíveis mecanismos

- Perfuração de camadas de óxido;
- Danos em trilhas microscópicas;
- Curtos-circuitos internos.

### Resultado

O componente pode:

- Parar de funcionar imediatamente;
- Não ligar;
- Falhar nos testes iniciais de hardware.

## 2. Dano latente — falha degradativa ou oculta

O componente pode ser enfraquecido sem parar de funcionar inicialmente.

Com o uso contínuo, o dano pode evoluir e provocar:

- Travamentos;
- Telas azuis;
- Perda de dados;
- Falhas intermitentes;
- Falha prematura.

---

# 📊 Comparativo de Sensibilidade à ESD

| Componente | Sensibilidade típica à ESD | Principais vulnerabilidades |
|---|---:|---|
| Processadores (CPUs/GPUs) | 10 V – 100 V | Milhões de transistores miniaturizados e portas de óxido extremamente finas. |
| Memórias (RAM/Flash) | 20 V – 200 V | Células de armazenamento de alta densidade. |
| Placas-mãe | 100 V – 500 V | Trilhas e controladores de comunicação. |

---

# 🛡️ Prevenção contra ESD

Para reduzir os riscos de descargas eletrostáticas durante manutenção e montagem de computadores:

- **Pulseiras e calcanhares antiestáticos:** conectam o operador ao aterramento.
- **Mantas ESD:** superfícies dissipativas para ferramentas e componentes.
- **Sacos antiestáticos:** protegem os componentes durante o transporte.
- **Controle da umidade:** ambientes abaixo de 40% de umidade relativa favorecem a geração de eletricidade estática.

---

# ♻️ Sustentabilidade e E-lixo

O **lixo eletrônico (e-lixo)** representa um importante desafio ambiental.

O técnico de TI possui responsabilidade na destinação correta dos equipamentos e componentes eletrônicos.

## Perigos presentes no hardware

### ☣️ Metais pesados

O manual cita:

- Chumbo;
- Cádmio;
- Mercúrio;
- Arsênio.

Quando descartados incorretamente, esses materiais podem contaminar o solo, a água e a cadeia alimentar.

### 🔋 Baterias

Podem apresentar riscos de:

- Incêndio;
- Vazamento;
- Liberação de gases tóxicos.

### 🧪 Plásticos bromados

Podem liberar substâncias perigosas quando queimados incorretamente.

---

# 🌱 Responsabilidade Socioambiental

O manual relaciona a **Política Nacional de Resíduos Sólidos (PNRS — Lei nº 12.305/2010)** à logística reversa de produtos eletroeletrônicos.

## Práticas fundamentais

### 1. Triagem e logística reversa

Separar:

- Placas;
- Fiações;
- Carcaças plásticas;
- Baterias.

Depois, encaminhar os materiais a pontos de coleta autorizados ou fabricantes.

### 2. Reparo e upcycling

Prolongar a vida útil do hardware.

**Exemplo:** substituir um HDD antigo por um SSD em vez de descartar todo o computador.

### 3. Conscientização e prática ética

Orientar clientes e empresas sobre o destino correto das peças antigas.

---

# 🔄 Ciclo do Descarte

| Resíduo | Descarte incorreto | Destinação correta |
|---|---|---|
| Baterias e pilhas | Vazamentos, contaminação e risco de incêndio | Coleta especializada, reciclagem e reaproveitamento |
| Placas e processadores | Liberação de metais no solo | Recuperação de materiais como ouro, prata e cobre |
| Monitores e telas | Quebra e liberação de substâncias perigosas | Desmontagem controlada e reciclagem |

---

# 📍 Logística Reversa em Manaus

## 1. Eco Cooperativa

**Endereço:** Av. Arquiteto José Henriques B. Rodrigues, 2374 — Colônia Terra Nova, Manaus — AM.

O manual cita como resíduos:

- Computadores;
- Gabinetes;
- Mídias;
- Mouses;
- Teclados;
- Celulares;
- Carregadores;
- Cabos;
- Placas de circuito impresso.

## 2. Manaus Limpa Soluções Ambientais

**Endereço:** Av. do Turismo, 13735 — Tarumã, Manaus — AM.

**Telefone informado no manual:** 92 3658-6108.

O documento cita:

- Computadores;
- Servidores;
- Placas-mãe;
- Celulares;
- Monitores;
- Periféricos.

> Recomenda-se verificar previamente as condições de recebimento.

## 3. Pontos de coleta permanente — Bemol

### Bemol Matriz

Rua Miranda Leão, 41 — Centro, Manaus — AM.

### Bemol Cidade Nova

Avenida Noel Nutels, 1762 — Cidade Nova, Manaus — AM.

### Bemol Manauara Shopping

Avenida Mário Ypiranga, 1300 — Adrianópolis, Manaus — AM.

O manual cita como resíduos aceitos:

- Notebooks;
- Tablets;
- Celulares;
- Modems;
- Roteadores;
- Impressoras;
- Ferramentas elétricas portáteis;
- Pilhas;
- Baterias usadas.

---

# 🛠️ Cuidados no Manuseio de Hardware

Os principais cuidados apresentados no manual foram baseados em documentos de fabricantes como **Gigabyte** e **ASUS**.

- Evite tocar em terminais metálicos, pinos expostos e conectores de solda.
- Segure a placa pelas bordas da PCB ou pelas estruturas dos dissipadores.
- Não remova adesivos de número de série ou selos de garantia.
- Ao fixar a placa no gabinete, evite contato inadequado dos parafusos com trilhas do circuito.

---

# ⚠️ Alertas de ESD

Os circuitos eletrônicos são altamente vulneráveis à eletricidade estática.

## Pulseira antiestática

É recomendado utilizar uma pulseira ESD conectada ao aterramento ao manusear:

- Placa-mãe;
- Processador;
- Memória RAM.

## Alternativa

Caso não possua uma pulseira ESD:

1. Mantenha as mãos secas.
2. Toque em um objeto metálico aterrado.
3. Faça isso antes de tocar no hardware.

## Superfície de trabalho

Mantenha a placa:

- Sobre uma manta antiestática; ou
- Dentro da embalagem blindada original.

---

# 🔌 Alertas de Energia

## 1. Desconectar a alimentação

Antes de instalar ou remover componentes:

> **Remova o cabo de força principal da tomada.**

## 2. Desligar a fonte

Antes de conectar ou desconectar cabos:

- Coloque a chave da fonte na posição **O (desligado)**.
- Tenha atenção especial aos conectores ATX de 24 pinos e CPU de 8 pinos.

## 3. Verificar a tensão

Antes de ligar o computador, confirme se a fonte está configurada corretamente para a tensão elétrica utilizada na região.

## 4. Conferir as conexões

Verifique se todos os conectores estão:

- Firmemente encaixados;
- Com as travas plásticas corretamente posicionadas;
- Sem sinais de mau contato.

---

# ✅ Checklist do Técnico

- [ ] Desligar o computador.
- [ ] Retirar o cabo de alimentação da tomada.
- [ ] Desligar a fonte.
- [ ] Utilizar proteção contra ESD.
- [ ] Trabalhar em superfície adequada.
- [ ] Segurar placas pelas bordas.
- [ ] Não tocar nos pinos e contatos metálicos.
- [ ] Verificar os cabos de alimentação.
- [ ] Conferir a tensão elétrica.
- [ ] Destinar corretamente componentes descartados.
- [ ] Preservar etiquetas e selos de garantia.

---

# 📚 Conclusão

A atuação de um técnico de informática envolve muito mais do que montar ou reparar computadores.

É necessário considerar:

- Ergonomia;
- Segurança elétrica;
- Proteção contra ESD;
- Manuseio correto dos componentes;
- Sustentabilidade;
- Destinação adequada do lixo eletrônico;
- Logística reversa;
- Responsabilidade profissional.

Seguir esses procedimentos ajuda a preservar os equipamentos, reduzir riscos e contribuir para uma atuação técnica mais segura e responsável.
