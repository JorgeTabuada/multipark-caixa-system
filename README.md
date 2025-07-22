# 🚗 Caixa Multipark - Sistema de Gestão de Entregas

Sistema web para gestão e validação de caixa de entregas de estacionamento.

## 🎯 O que faz

- **Importa** dados do Odoo, Back Office e folhas de caixa
- **Compara** automaticamente os sistemas
- **Valida** entregas por condutor  
- **Gera** relatórios Excel completos
- **Dashboard** com estatísticas em tempo real

## 🛠️ Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Backend:** Supabase (PostgreSQL + Auth)
- **Libs:** XLSX.js, Chart.js
- **Deploy:** GitHub Pages

## 🚀 Como usar

1. **Login** com credenciais
2. **Importar** ficheiros Excel (Odoo + Back Office)
3. **Resolver** inconsistências encontradas
4. **Importar** ficheiro de caixa dos condutores
5. **Validar** entregas uma a uma
6. **Ver** dashboard com estatísticas
7. **Exportar** relatório final

## 🔧 Setup Local

```bash
# Clone do repo
git clone https://github.com/JorgeTabuada/multipark-caixa-system.git
cd multipark-caixa-system

# Servidor local
python -m http.server 8000
# ou
npx live-server
```

## 🎪 Demo

**URL:** `https://jorgetabuada.github.io/multipark-caixa-system`

**Utilizadores de teste:**
- `admin@multipark.com` / `admin123`
- `user@multipark.com` / `user123`

## 📚 Supabase Config

**URL:** `https://uvcmgzhwiibjcygqsjrm.supabase.co`

Schema completo em `schema.sql`

## 🎨 Screenshots

![Dashboard](docs/dashboard-preview.png)
*Dashboard com estatísticas em tempo real*

## 📝 TODO

- [ ] Testes automatizados
- [ ] PWA support
- [ ] Notificações push
- [ ] API REST
- [ ] Mobile app

---

Feito com ❤️ para simplificar a gestão de caixa!