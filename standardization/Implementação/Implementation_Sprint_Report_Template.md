# 🧩 Implementation Sprint Report #NUMBER
📅 **Período:** DD/MM/AAAA a DD/MM/AAAA  
🔁 **Sprint Duration:** (ex: 1 semana)

---

## 👥 Equipe Responsável
- Nome 1 – Função/Responsabilidade
- Nome 2 – Função/Responsabilidade
- Nome 3 – Função/Responsabilidade

---

## 🎯 Metas do Sprint
Descreva aqui os objetivos principais deste ciclo:

- 🧱 Montar a base estrutural do braço
- 🧪 Testar acionamento de motores
- 🔌 Preparar cabeamento da placa
- 🎯 Avançar na lógica de controle via Arduino

---

## 📌 Resumo de Execução

| Área / Módulo              | Progresso     | Responsável |
|----------------------------|---------------|-------------|
| 🧱 Estrutura física         | ⬜⬜🟨🟨🟨🟨🟩🟩🟩🟩 (40%) | Nome        |
| 🔌 Eletrônica               | ⬜⬜⬜🟨🟨🟨🟨🟩🟩🟩 (30%) | Nome        |
| 💻 Programação (Arduino)    | ⬜⬜⬜⬜🟨🟨🟩🟩🟩🟩 (40%) | Nome        |
| 👁️ Visão Computacional      | ⬜⬜⬜⬜⬜🟨🟨🟩🟩🟩 (30%) | Nome        |
| 🔗 Integração de sistemas   | ⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜ (0%)   | Nome        |

> ⬜ = não iniciado, 🟨 = em andamento, 🟩 = concluído

---

## ✅ Tarefas Concluídas no Sprint

### 🔩 Estrutura Física
- [x] Fixação da base com parafusos M3
- [ ] Impressão da nova garra (aguardando término)
- [ ] Montagem da articulação do ombro

### 🔌 Eletrônica
- [ ] Soldagem dos conectores dos motores
- [x] Teste de funcionamento da fonte de 12V
- [ ] Verificação de possíveis curtos

### 💻 Programação
- [x] Subida do firmware no Arduino
- [ ] Testes com motor de passo via código
- [ ] Calibração de movimentos

---

## ⚠️ Problemas Encontrados
- 🔥 **Superaquecimento** no motor 2 após 5 minutos de uso
- 📉 **Falha de leitura** no sensor ACS712
- 🧷 **Alinhamento impreciso** do braço devido à folga na peça impressa

---

## 💡 Análises e Decisões Técnicas
- ✅ Usar **dissipadores de calor** nos drivers A4988
- ✅ Reimprimir suporte com **PETG** e **infill maior**
- ✅ Adotar **conectores JST** para padrão de cabeamento

---

## 📸 Evidências Visuais
> [📷 Foto da base montada](link-da-imagem)  
> [📷 Driver A4988 em funcionamento](link-da-imagem)  
> [🎥 Vídeo de teste com o motor 1](link-do-video)

---

## 🔄 Pendências e Ações para o Próximo Sprint
- [ ] Concluir impressão da articulação do cotovelo
- [ ] Finalizar testes com sensores ACS712 e driver alternativo
- [ ] Documentar ligações elétricas em `docs/hardware/esquematicos/`
- [ ] Iniciar testes de comunicação entre módulos

---

## 📚 Anexos (opcional)
- `circuito_motor_A4988_v2.fzz`
- `garra_v3.stl`
- `sprint_backlog.xlsx`

---

> 📝 **Observação final:** este relatório foi elaborado de forma colaborativa durante a reunião técnica de DD/MM/AAAA.
