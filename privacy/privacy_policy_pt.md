# Política de Privacidade — BabyCare+

**Última actualização:** 13 de Setembro de 2026

Esta Política de Privacidade descreve como a aplicação **BabyCare+** ("nós", "a app") recolhe, utiliza e protege informações dos utilizadores. Ao instalar e utilizar a app, concorda com as práticas descritas neste documento.

---

## 1. Quem somos

- **Responsável pelo tratamento:** Murilo Chechá
- **Email de contacto:** muchecha@gmail.com
- **App:** BabyCare+
- **Plataforma:** Android (Google Play Store)

---

## 2. Idade mínima

A BabyCare+ é destinada exclusivamente a **adultos com 18 anos ou mais** (pais, mães ou cuidadores). A app **não se destina a ser utilizada por crianças**. Não recolhemos intencionalmente dados de crianças menores de 18 anos.

Em particular, não nos dirigimos a crianças menores de 13 anos e não recolhemos intencionalmente dados pessoais de crianças menores de 13 anos. Se tomarmos conhecimento de que recolhemos dados pessoais de uma criança menor de 13 anos sem verificação do consentimento parental, tomaremos medidas para remover essa informação dos nossos servidores.

---

## 3. Dados que recolhemos

### 3.1 Dados que o utilizador fornece directamente
- **Conta:** email, nome e foto de perfil obtidos via Google Sign-In.
- **Dados do bebé:** nome, sexo, data de nascimento, foto, relação familiar (mãe, pai, ama, etc.), cor de moldura.
- **Registos de actividade:** sono, amamentação, biberão, sólidos, fralda, banho, choro, hospital, notas, fotos do diário, etc.
- **Medições:** peso, altura, perímetro cefálico, temperatura.
- **Saúde:** vacinas administradas, medicamentos (pílulas) tomados.
- **Membros da família:** convites enviados/aceites entre cuidadores que partilham o cuidado do mesmo bebé.
- **Lembretes:** horários e mensagens personalizadas de notificações configuradas pelo utilizador.

### 3.2 Dados recolhidos automaticamente
- **Identificadores de publicidade (Google Ad ID)** e endereço IP, recolhidos pela SDK Google Mobile Ads para servir publicidade.
- **Logs de erros** anonimizados, para diagnosticar bugs.

### 3.3 Dados que **não** recolhemos
- Localização GPS.
- Contactos do dispositivo.
- Histórico de chamadas ou SMS.
- Microfone.

---

## 4. Como armazenamos os dados

- **Backend:** os dados são armazenados em [Supabase](https://supabase.com), uma plataforma de base de dados PostgreSQL com encriptação em repouso (AES-256) e em trânsito (TLS 1.2+).
- **Localização dos servidores:** EU/US (consoante a região do projecto Supabase).
- **Acesso:** apenas o utilizador autenticado e os membros que ele convidou explicitamente para a "família" do bebé conseguem aceder aos dados desse bebé. Aplicamos Row Level Security (RLS) no Supabase para garantir esse isolamento.
- **Cache local:** alguns dados são guardados localmente no dispositivo via SharedPreferences e SQLite para funcionamento offline.

---

## 5. Como utilizamos os dados

- Apresentar a timeline de actividades do bebé.
- Sincronizar dados entre dispositivos do mesmo cuidador e entre cuidadores convidados.
- Enviar notificações locais com base nos lembretes configurados pelo utilizador (estas notificações **não** saem do dispositivo).
- Servir publicidade (banner e intersticial) através do Google AdMob — necessário para sustentar a versão gratuita.

Não vendemos, alugamos nem partilhamos os seus dados pessoais com terceiros para fins de marketing.

---

## 6. Partilha de dados com terceiros

| Serviço | Propósito | Dados partilhados |
|---|---|---|
| **Supabase** | Armazenamento de dados | Todos os dados de conta e do bebé |
| **Google Sign-In** | Autenticação | Email, nome, foto de perfil |
| **Google AdMob** | Publicidade | Ad ID, IP, dados técnicos do dispositivo |

Os links para as políticas de privacidade dos terceiros:
- Supabase: https://supabase.com/privacy
- Google: https://policies.google.com/privacy

---

## 7. Os seus direitos (LGPD / RGPD)

Tem direito a:
- **Aceder** aos dados que detemos sobre si.
- **Rectificar** dados incorrectos.
- **Eliminar** a sua conta e todos os dados associados.
- **Exportar** os seus dados num formato legível.
- **Oposição** ao tratamento, retirando o seu consentimento a qualquer momento.

Para exercer qualquer destes direitos, envie um email para **muchecha@gmail.com** com a frase "Pedido LGPD/RGPD" no assunto e o email associado à conta. Respondemos em até 30 dias.

---

## 8. Eliminação de conta

Pode eliminar a sua conta de duas formas:

1. **Dentro da app:** aceda a *Configurações → Eliminar conta*. A exclusão é imediata e apaga permanentemente a sua conta, os bebés que registou, actividades, lembretes e fotos associadas. Se for dono de um bebé partilhado com outros membros da família, precisa de remover esses membros antes de conseguir eliminar a conta — para não apagar o histórico deles sem aviso.
2. **Por email:** enviando uma mensagem para **muchecha@gmail.com** com o assunto "Eliminar conta", incluindo o email da conta. Confirmaremos a eliminação em até **15 dias úteis**.

---

## 9. Cookies e tecnologias semelhantes

A app utiliza armazenamento local (SharedPreferences, SQLite) apenas para fins de funcionamento offline e cache. Não utilizamos cookies de tracking de terceiros para além do necessário pela SDK do Google AdMob.

---

## 10. Segurança

Adoptamos medidas técnicas e organizativas adequadas para proteger os dados pessoais:
- Comunicação cifrada (HTTPS/TLS).
- Autenticação OAuth2 via Google.
- Row Level Security no Supabase para garantir isolamento entre utilizadores.
- Acesso ao backend restringido por chaves API.

Apesar destas medidas, nenhum sistema é 100% seguro. Em caso de incidente de segurança que afecte os seus dados, comunicaremos no prazo de 72 horas conforme a lei.

---

## 11. Alterações a esta política

Reservamo-nos o direito de actualizar esta Política. Alterações significativas serão notificadas via app e/ou email. Continuar a usar a app após uma actualização constitui aceitação da nova versão.

---

## 12. Contacto

Para qualquer questão sobre esta Política de Privacidade ou sobre o tratamento dos seus dados:

**Email:** muchecha@gmail.com
