# ProjetoIntegrador_AcademiaNeon
Projeto Integrador para a Academia Neon DevOps - Grupo DevOpers - Utilizando Ansible, Docker, Jenkins, AWS


# Sobre o Projeto Integrador
Introdução: Será fornecido um APP feito em NodeJS que escreve e lê arquivos no S3. As configurações necessárias para esse app funcionar serão definidas por variáveis de ambiente (environment)

O objetivo: Criar as duas máquinas de app na AWS junto com uma máquina que conterá o Jenkins (para facilitar a evolução
fora da sala de aula). Com o jenkins no ar elas deverão construir as pipelines clonando o projeto, executando os testes e configurando 
com as devidas variáveis de ambiente e por fim publicando no ambiente de destino: Prod ou Homolog

Resultados Esperados: Com os aplicativos NodeJS no ar as alunas devem observar a url /healthcheck de cada um deles para ver se foram ou não configurados com sucesso. Deverão testar a ação de upload de imagens da aplicação que foi fornecida e se estiver com os tokens corretos do S3 fará o upload com sucesso.

# Arquitetura


# Provisionando EC2 + S3 + ACL + ECR na AWS


# Configurando Maquinas EC2 


# APP NodeJS utilizado

https://github.com/bgsouza/digitalhouse-devops-app


# Pipeline Jenkins
