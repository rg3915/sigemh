# SIGEMH - Sistema Integrado de Gestão de Equipamentos Médico-Hospitalares

Projeto __Open Source__ para Gestão de Equipamentos Médico-Hospitalares.

Um projeto piloto está sendo desenvolvido no Hospital Universitário Onofre Lopes - Natal/RN

## Sou desenvolvedor, como posso contribuir?

1. Clone o repositório do GitHub no botão verde;
2. Crie um ambiente virtual com o Python 3.6 e o Django==1.9.6
3. Ative o virtualenv;
4. Instale as dependências;
5. Configure a instância com o `.env`
6. Execute os testes.

```
git clone https://github.com/victoracioly/sigemh.git
cd sigemh
python3 -m venv .venv
source .venv/bin/activate
# Se for no Windows .venv\Scripts\activate.bat
pip install -r requirements.txt
cp contrib/env-sample .env
python manage.py test
```