# PES6 Mobile PS2 — base inicial

Projeto Android inicial para a interface do aplicativo e seleção de imagens ISO de PS2.

## O que já existe nesta base
- Projeto Android em Kotlin/Gradle.
- Aplicativo em orientação horizontal.
- Seletor de arquivos para escolher uma ISO.
- Esboço visual dos controles de futebol.
- GitHub Actions para compilar e disponibilizar um APK de depuração.

## O que ainda NÃO está implementado
- **Não contém emulador/núcleo de PS2.**
- **Não executa o PES 6 nem qualquer ISO ainda.**
- **Não contém backend Vulkan.** Vulkan é um requisito planejado, não uma função pronta.
- Os botões de jogo são apenas visuais nesta etapa.

Para executar uma ISO, será necessário integrar um núcleo de emulação de PS2 compatível com Android, respeitar sua licença e implementar a comunicação entre o app e o núcleo. Também será necessário testar o backend Vulkan no aparelho real.

## Compilar na nuvem
1. Envie todos os arquivos desta pasta para a raiz do repositório GitHub.
2. Abra a aba **Actions**.
3. Se necessário, autorize os workflows.
4. Execute **Build Android APK** em **Run workflow**, ou faça um commit.
5. Quando terminar, abra a execução e baixe o artefato `PES6-Mobile-PS2-debug`.

O artefato é uma APK de protótipo da interface, não um emulador funcional.
