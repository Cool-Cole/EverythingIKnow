# Reverse Engineering: Getting started

## Inspirational reading

[Bruce Schneier: The Security Mindset (2008)](https://www.schneier.com/blog/archives/2008/03/the_security_mi_1.html)

[How I cut GTA Online loading times by 70% (2021)](https://nee.lv/2021/02/28/How-I-cut-GTA-Online-loading-times-by-70/)

[Legalizing Gay Marriage in Crusader Kings III with Ghidra (2021)](https://waffleironer.medium.com/legalizing-gay-marriage-in-crusader-kings-iii-with-ghidra-2602e6aa8689)

[Modding LEGO Island 2 part 1 (2021)](https://robbebryssinck.github.io/Modding-an-old-game-which-hardcodes-nearly-everything-LEGO-Island-2-part-1-of-2/)

[Modding Lego Island 2 part 2 (2021)](https://robbebryssinck.github.io/Modding-an-old-game-which-hardcodes-nearly-everything-LEGO-Island-2-part-2-of-2/)

## Free Guides

[Introduction to Reverse Engineering with Ghidra](https://hackaday.io/course/172292-introduction-to-reverse-engineering-with-ghidra)

[Reverse engineering course by 0xZ0F (2020)](https://github.com/0xZ0F/Z0FCourse_ReverseEngineering) (More reasources in the associated [HN Discussion](https://news.ycombinator.com/item?id=22061842))

[Publicly Available Courses and Materials (2020)](https://www.voidstarsec.com/free-courses-materials)

[Reverse Engineering
for Beginners](https://www.begin.re/) ([HN Discussion](https://news.ycombinator.com/item?id=17424057))

[Introduction to x64 Assembly (2012)](https://software.intel.com/content/www/us/en/develop/articles/introduction-to-x64-assembly.html) (HN Discussions [here](https://news.ycombinator.com/item?id=10773849) and [here](https://news.ycombinator.com/item?id=5498272)) (TODO - check one of the HN links)

## Paid Guides

[The Ghidra Book (2020)](https://nostarch.com/GhidraBook)

[Reversing Hero (2019)](https://www.reversinghero.com/) - 15 challenges in one binary. The binary is free however the 12 hours of accompanying solution videos are not.

[Reverse Engineering for Beginners (2014, last updated 2021)](https://beginners.re/main.html) - A 2020 copy of the book can be viewed [here](https://web.archive.org/web/20201111234229/https://beginners.re/RE4B-EN.pdf) ([HN Discussion](https://news.ycombinator.com/item?id=21640669))

## Free Tools

[Ghidra](https://ghidra-sre.org/) - An open source static binary analysis tool written by the NSA [HN Discussion](https://news.ycombinator.com/item?id=19315273)

[Binwalk](https://github.com/ReFirmLabs/binwalk) - An open source program that allows for binary static analysis. Mainly used to find out what kinds of files are hidden in executables and firmware.

[AES Finder](https://github.com/MantechUser/aes-finder) - A utility to find AES keys in running process memory ([HN Discussion](https://news.ycombinator.com/item?id=24390883))

[File (UNIX command)](https://www.man7.org/linux/man-pages/man1/file.1.html) - Used to detect the file types of unkown binaries  [Good Wikipedia artical about it here](https://en.wikipedia.org/wiki/File_(command))

[Strings (UNIX command)](https://www.man7.org/linux/man-pages/man1/file.1.html) - Used to find strings in binaries

[ltrace (UNIX command)](https://www.ltrace.org/) - ltrace intercepts and records dynamic library calls which are called by an executed process and the signals received by that process. It can also intercept and print the system calls executed by the program. ([Man Page](https://www.man7.org/linux/man-pages/man1/ltrace.1.html))
