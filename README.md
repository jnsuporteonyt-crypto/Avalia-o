# Avaliação Quinzenal — Protocolo Premium

App PWA para acompanhamento de avaliação física quinzenal com 27 variáveis validadas.

## 📁 Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | App completo (HTML + CSS + JS em um arquivo) |
| `manifest.json` | Configuração PWA (instalar como app) |
| `sw.js` | Service Worker (funciona offline) |
| `icon-192.png` | Ícone 192×192 (use o do repositório anterior) |
| `icon-512.png` | Ícone 512×512 |

## 🚀 Como usar no GitHub Pages

1. Faça upload dos 5 arquivos no repositório
2. Vá em **Settings → Pages → Source: main branch / root**
3. Acesse `https://seuusuario.github.io/nome-do-repo/`

## 🔐 Login

- Tela de cadastro: nome, peso, altura, modalidade, usuário e senha
- Dados salvos em `localStorage` do navegador (por dispositivo)
- Múltiplos alunos no mesmo dispositivo

## 📊 Funcionalidades

- **Nova Avaliação** — preencha os testes disponíveis (27 variáveis)
- **Tabela** — planilha com baseline + até 6 avaliações, semáforo verde/amarelo/vermelho
- **Histórico** — lista de todas as avaliações com detalhes
- **Relatório** — comparativo baseline vs atual com delta e percentual
- **Perfil** — editar dados do aluno e senha

## 📋 Testes incluídos

| Código | Teste | Meta |
|---|---|---|
| T01 | Knee-to-Wall D/E | > 10 cm |
| T02 | Calf Raise D/E | > 25 reps |
| T03 | Flexão Joelho D/E | > 140° |
| T04 | Wall Squat D/E | > 60s |
| T05 | Single-leg Squat D/E | 10/10 verdes |
| T06 | Nordic Hamstring D/E | > 4s |
| T07 | Hip Abduction D/E | > 20 reps |
| T08 | Balance D/E (olhos abertos) | > 45s |
| T09 | Step-Down D/E (verdes) | 10/10 |
| T10 | Triple Hop D/E + IS | IS > 90% |
| T11 | Rotação Interna Quadril D/E | > 20° |
| T12 | VAS + IKDC + Tampa Scale | VAS < 2 |

## 🟢🟡🔴 Semáforo de Progresso

- **Verde** — melhora ≥ 5% em relação à avaliação anterior  
- **Amarelo** — estável (+/- 4%)  
- **Vermelho** — piora em relação à avaliação anterior

---

*Baseado no Protocolo de Avaliação Biociné­tica (Leporace D.Sc. | Machado M.Sc.) — uso profissional.*
