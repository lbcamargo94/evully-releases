# Evully — releases

Este repositório contém **apenas os instaladores** do Evully para Windows.
O código-fonte é privado.

O app instalado procura atualizações aqui e só instala uma versão nova
quando você pede. Cada instalador tem:

- `Evully-Setup-<versão>.exe.sha256`: hash SHA-256 para conferência manual;
- `Evully-Setup-<versão>.exe.sig`: assinatura digital verificada pelo app
  antes de instalar.

Seus dados ficam em `%APPDATA%\Evully` e são mantidos nas atualizações.
