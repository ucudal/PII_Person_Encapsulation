<img alt="UCU" src="https://www.ucu.edu.uy/plantillas/images/logo_ucu.svg"
width="150"/>

# Universidad Católica del Uruguay

## Programación II

# Clase `Person` encapsulada

## Objetivo

> [!NOTE]
>
> Crea tu propio repositorio a partir de esta plantilla y clona ese repositorio
> en tu equipo.

<!-- Intentionally left blank -->

> [!IMPORTANT]
>
> Para compilar el código en Visual Studio Code ejecuten el comando `Run Build
> Task...` del menú `Terminal` y elijan `dotnet: build`.

<!-- Intentionally left blank -->

Agrega la clase `Person` con las responsabilidades de conocer el nombre `Name` y
la cédula `Id` de forma que sólo acepte nombres y cédulas válidas:

- El nombre es válido si no está en blanco.
- La cédula es válida si es correcto el dígito verificador.

Usen el código provisto en el adjunto como punto de partida. La clase
[`IdUtils`](./src/Library/IdUtils.cs) tiene un método `bool IdIsValid(string)`
que verifica si una cédula es válida. El programa en el método `void Main()` de
la clase [`Program`](./src/Program/Program.cs) incluye la creación de personas
con nombre y cédulas válidos y la modificación de esa información con valores
válidos e inválidos.

> [!NOTE]
>
> El código en el método `Main` de `Program` está comentado. Quita los
> comentarios para probar tu programa.

No incluye el código de la clase Person, que deberán programar ustedes a partir
del [ejercicio](https://github.com/ucudal/PII_Identificar_partes_de_objeto) de
identificar las partes de un objeto.

## Uso de ![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-000?logo=githubcopilot&logoColor=fff)

Es posible usar GitHub Copilot en este repositorio. Consulta [cómo usar Copilot
para aprender](./COPILOT.md).
