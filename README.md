# paperlog
This is a LaTex project for generating paper ham logbook pages

For adujusting to your needs edit the paperlog.tex file and compile.
You should at least edit the follwing section:
```latex 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% Start here editing!
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\newcommand{\logpages}{20}      %How many logpages do you want?
\newcommand{\callsign}{DB3DE}   %What is your callsign
\newcommand{\startdate}{}       %What is the startdate of this logbook - put \today for ... today
\newcommand{\lastdate}{}        %Fill this if you want a stopdate 
\newcommand{\includerst}{}      %include the RST mapping at the last pages - remove by commenting using a %
\newcommand{\includebandplan}{} %include the bandplan files - remove by commenting using a %

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% Stop here editing!
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
```
A sample page looks like this:
![Sample Logpage](https://github.com/DB3DE/paperlog/blob/master/samples/sample_page.png)

[Sample PDF](https://github.com/DB3DE/paperlog/blob/master/samples/sample_logbook.pdf)