# GCC 运行时库例外条款

> This is an unofficial translation of the GCC Runtime Library Exception into Simplified Chinese. It was not published by the Free Software Foundation, and does not legally state the distribution terms for documentation that uses the GCC RLE—only the original English text of the GCC RLE does that. However, we hope that this translation will help Simplified Chinese speakers understand the GCC RLE better. 
>
> 这是 GCC 运行时库例外（RLE） 的非正式简体中文翻译。它并未被自由软件基金会发行，也不对使用 GCC RLE 发布的文档起法律效力——只有 GCC RLE 的原始英文版才有法律意义。不过，我们希望该翻译能够帮助简体中文用户更好地理解 GCC RLE。
>
> 只有按照 [http://www.gnu.org/licenses/translations.html](https://www.gnu.org/licenses/translations.html) 的条款，你才能发布此翻译，无论是否修改过。
>
> Luke Na 依照 GNU 的要求而附加的声明，2023 年 3 月 30 日。

版本 3.1，2009 年 3 月 31 日

版权所有 © 2009 Free Software Foundation, Inc. https://fsf.org/

每个人都可以复制和分发本许可证文件的原始副本，但不允许更改。

本 GCC 运行时库例外条款（以下称为本“例外”）是 GNU 通用公共许可证第 3 版（“GPLv3”）第 7 节下的一项附加许可证。它适用于某个特定的文件（“运行时库”），该文件包含一个由文件的版权持有人放置的声明，说明该文件受 GPLv3 以及本条款管辖。

当您使用 GCC 编译程序时，GCC 可能会将某些 GCC 头文件和运行时库的部分内容与编译后的程序结合起来。本例外条款的目的是允许编译非 GPL（包括专有）程序，以此方式使用本例外所涵盖的头文件和运行时库。

## 0. 定义

如果某个文件在编译过程后需要运行时库来执行，或者使用运行时库提供的接口，但（本身）不是基于运行时库（构建）的，则该文件为“独立模块”。

“GCC” 指的是 GNU 编译器集合（GCC）的某个版本，无论做出修改与否，受 GNU General Public License（GPL）第 3 版（或指定的较新版本）管辖，且具有使用由 FSF 发布的任何后续版本的选项。

“GPL 兼容软件” 指其传播、修改和使用条件允许与 GCC 合并的软件，符合 GCC 的许可证。

“目标代码”指任何编译器为真实或虚拟目标处理器体系结构生成的输出，可以是可执行形式，或者适合输入到汇编程序、装载器、链接器和/或执行阶段。尽管如此，目标代码不包括用作编译器中间表示形式或用于生成编译器中间表示形式的任何格式的数据。

“编译过程”将完全以人类编写的非中间语言和/或 Java 虚拟机字节码表示的代码转换为目标代码。因此，例如，使用源代码生成器和预处理器不需要被视为编译过程的一部分，因为可以将编译过程理解为从生成器或预处理器的输出开始。

如果使用 GCC，单独或与其他 GPL 兼容软件一起进行编译，或者如果没有使用基于 GCC 的任何作品，则编译过程是“符合资格的”。例如，使用非 GPL 兼容软件优化任何 GCC 中间表示形式不符合符合资格编译过程的标准。

## 1. 附加授权的授予 
您有权传播通过将运行时库与独立模块组合而成的目标代码作品，即使这种传播本来会违反 GPLv3 的条款，前提是所有的目标代码都是由符合资格的编译过程生成的。然后，您可以按照您的选择将这种组合传达，与独立模块的许可证一致。

## 2. 不削弱 GCC 版权条款的效力 
此例外的可用性并不意味着有一般的假设认为第三方软件不受 GCC 许可证的版权保护要求的影响。