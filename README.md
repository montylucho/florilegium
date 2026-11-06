# a ConTeXt LMTX installation (the standalone distribution): its tree for
 modules
cd /path/to/context/tex/texmf-modules && unzip/path/to/t-florilegium.zip
mtxrun --generate
Usage:

\usemodule[florilegium][composition=grown]


\setupflorilegium

[composition=grown,

margin=yes,

visitors=yes,

sections=no,

aging=no,

theme=,

density=1,

intensity=1,

seed=]


\definecolor[ink][h=5B2A1F]

\definecolor[accent][h=B4662F]


\starttext

\florilegiuminitial[5]{E}very page grows its own garden ...

... \florilegiumbloom[lily] ...

\florilegiumtheme{geometric}

\florilegiumage{0.8}

\florilegiumornament[size=2em,ink=5B2A1F,angle=20,seed=random]{flower}

\florilegiumtextend

\stoptext
