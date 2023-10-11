<!---
Desenvolvedor apaixonado em busca de soluções criativas. Comprometido com o aprendizado contínuo e colaboração em projetos inovadores.
Passionate developer on a quest for creative solutions. Committed to continuous learning and collaboration on innovative projects.
@Njeskjarol @Njesk
--->

@echo off
:start
echo Escolha uma opção:
echo 1. Português
echo 2. English

set /p escolha=1-Português ou/or 2-English?: 

if "%escolha%"=="1" (
echo +-------------------------------------------------------------------------------------+
echo +----- 👋 Olá, me chamo Israel Macedo ( Njeskj )
echo +----- 👀 Tenho interesse em aprender linguagens de programação para ser FULL STACK
echo +----- 🌱 Atualmente, estou aprendendo JavaScript, PHP e SQL.
echo +----- 💞️ Estou procurando colaborar em projetos Front-End com bancos de dados.
echo +----- 📫 Chama no Instagram @israelmacedo.edf
echo +-------------------------------------------------------------------------------------+
    goto :fimpt
)

if "%escolha%"=="2" (
echo +-------------------------------------------------------------------------------------+
echo +----- 👋 Hello, my name is Israel Macedo (N jeskj )
echo +----- 👀 I'm interested in learning programming languages to become a FULL STACK developer
echo +----- 🌱 Currently, I'm learning JavaScript, PHP, and SQL.
echo +----- 💞️ I'm looking to collaborate on Front-End projects with databases.
echo +----- 📫 You can reach me on Instagram at @israelmacedo.edf.
echo +-------------------------------------------------------------------------------------+
    goto :fimen
)

echo Opção inválida. Por favor, escolha 1 ou 2.
pause >nul
goto :start

:fimpt
echo Tarefa concluída com sucesso. Obrigado por usar este script.
pause >bul
exit

:fimpt
echo Task completed successfully. Thank you for using this script.
pause >nul
exit
