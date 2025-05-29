# InformeTecnico
# Codigo OVERLEAF para obtener producto Informe Tecnico de Prog. Presupuestal 0040
\documentclass[11pt]{article}
\usepackage[spanish]{babel}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{geometry}
\usepackage{ragged2e}
\usepackage{ltablex}
\usepackage{multirow}
\keepXColumns
\renewcommand\tabularxcolumn[1]{m{#1}}
\usepackage{longtable}
\usepackage{array}
\usepackage{float}
\usepackage{fancyhdr}
\usepackage{titlesec}
\usepackage{caption}
\usepackage{colortbl}
\usepackage{multirow}
\usepackage{amsmath}
\usepackage{helvet}
\usepackage{tocloft}

% Anchos para secciones y subsecciones ya existentes
\setlength{\cftsecnumwidth}{2em} % Ancho para números de sección
\setlength{\cftsubsecnumwidth}{2.3em} % Ancho para números de subsección
\setlength{\cftsubsecindent}{2.4em} % Sangría para subsecciones

% --- Ajustes para subsubsecciones ---
\setlength{\cftsubsubsecnumwidth}{3em}   % Ancho para números/letras de subsubsección
\setlength{\cftsubsubsecindent}{5em}     % Sangría para subsubsecciones (ajustar según convenga)
\usepackage{xcolor} 
\usepackage{enumitem}
\renewcommand{\familydefault}{\sfdefault} % Calibri-like font
\setlength{\belowcaptionskip}{0pt}
% Definir el color personalizado
\definecolor{mygreen}{HTML}{538135}

% Cambiar el formato de las secciones
\titleformat{\section}[block]
  {\normalfont\Large\bfseries\color{mygreen}}  % Estilo de la sección (fuente, tamaño, color)
  {\Roman{section}.}{1em}{}

% Cambiar el formato de las subsecciones
\titleformat{\subsection}[block]
  {\normalfont\large\bfseries\color{mygreen}}  % Estilo de la subsección
  {\thesection.\arabic{subsection}}{1em}{}

% Numeración para subsubsection con letras (a, b, c)
\renewcommand{\thesubsubsection}{\thesubsection.\alph{subsubsection}}
\titleformat{\subsubsection}[runin]
  {\normalfont\normalsize\bfseries\color{mygreen}}
  {\thesubsubsection}{1em}{}

% Numeración para paragraph (4to nivel) con paréntesis y numeración romana minúscula
\renewcommand{\theparagraph}{\thesubsubsection(\roman{paragraph})}
\titleformat{\paragraph}[runin]
  {\normalfont\normalsize\bfseries\color{mygreen}}
  {\theparagraph}{1em}{}

% Incluir hasta el nivel paragraph en el índice
\setcounter{tocdepth}{4}

% Ajuste de los márgenes
\geometry{top=2.5cm, bottom=2.5cm, left=3cm, right=3cm}

\title{Informe del Programa Presupuestal 0040 \\ \large Mejora y Mantenimiento de la Sanidad Vegetal}
\author{Oficina de Planeamiento}
\date{}

\captionsetup[table]{font=small, labelfont=bf}


\begin{document}

\maketitle
\newpage  % <-- Salto para separar la carátula del índice

\tableofcontents
\newpage  % <-- Salto para separar el índice del contenido siguiente

\section{Presentación}

\noindent El Plan Estratégico Multisectorial del Sector Agrario y de Riego al 2030 establece 4 objetivos estratégicos sectoriales: 
1) Mejorar el aprovechamiento sostenible de los recursos naturales en el sector agrario, 
2) Incrementar la resiliencia y mitigación al cambio climático del Sector Agrario, 
3) Elevar la productividad de los sistemas productivos agrarios y 
4) Incrementar el acceso al mercado de productos agrarios. 
El tercer objetivo estratégico sectorial está orientado a elevar los niveles de productividad, basados en el aprovechamiento sostenible de los recursos naturales y contribuir al bienestar económico de los/las productores/as agrarios/as, contribuyendo a la seguridad alimentaria. Por otro lado, el Plan Estratégico Institucional 2021-2027 ampliado del Servicio Nacional de Sanidad Agraria tiene 3 objetivos estratégicos institucionales, siendo el primero “Mejorar las condiciones sanitarias en la producción animal, vegetal y procesamiento primario de alimentos agropecuarios y piensos de los productores agrarios y actores de la cadena agroalimentaria”. Este objetivo está articulado a los resultados del Programa Presupuestal 0040 Mejora y Mantenimiento de la Sanidad Vegetal, el cual abarca el control y/o erradicación de plagas prioritarias, el diagnóstico y vigilancia de plagas presentes y la prevención de la introducción de nuevas plagas a través de inspecciones y control de importaciones, así como la certificación fitosanitaria y la gestión necesaria para cumplir con las restricciones sanitarias exigidas por los mercados de destino, buscando que los productores comercialicen sus productos de manera segura y competitiva.
\\

\noindent La Oficina General de Planeamiento y Presupuesto en el marco de sus funciones realiza el seguimiento de programas presupuestales adscritos a través de la Oficina de Planeamiento en coordinación con las unidades de organización que correspondan, con el fin de generar información sobre el desempeño de los actores involucrados en la implementación de los programas, contribuyendo así en la toma de decisiones informadas para mejorar el desempeño.
\\

\noindent La implementación de los programas presupuestales representa un reto significativo para el sector, ya que involucra a diversos actores de los tres niveles de gobierno que deben colaborar estrechamente para implementar con idoneidad, optimización de recursos y claridad las estrategias y la entrega de productos.
\\

\noindent El presente informe analiza el desempeño del Programa Presupuestal 0040 Mantenimiento y Mejora de la Sanidad Vegetal al término del 2024, con la finalidad de dar cuenta en qué medida el programa presupuestal está ejecutando la provisión de productos y ejecución de inversiones, así como el cumplimiento de las metas de los indicadores que evalúan el desempeño.
\vspace{-0.3cm}


\section{Contenido del Programa}

\subsection{Creación del Programa} 

\noindent El Programa Presupuestal 0040: Mejora de la Sanidad Vegetal surge como una respuesta estratégica a las situaciones adversas enfrentadas por el subsector agrícola en el Perú. Este subsector está constantemente amenazado por la presencia de enfermedades que afectan la calidad de los productos agrícolas y la productividad, perjudicando directamente a los productores.
\\

\noindent Fue presentado para el ejercicio fiscal 2013 por el entonces Ministerio de Agricultura y Riego, con el propósito de priorizar la ejecución de productos y proyectos que lo conforman, orientados al logro de resultados inmediatos e intermedios programados.
\\

\noindent Las exigencias sanitarias de los mercados internacionales continúan aumentando, obligando a los países exportadores a cumplir con estrictos estándares de sanidad vegetal. En este contexto, el Perú identificó la necesidad de desarrollar un programa específico que no solo busca incrementar la cantidad de productores agrícolas con condiciones fitosanitarias para productos vegetales sanos, sino también aumentar el número de productores agrícolas con acceso a mercados globales.


\subsection{Diseño del Programa Presupuestal}

\noindent El Programa Presupuestal 0040 presenta un enfoque integral que se centra en tres áreas claves: el control y/o erradicación de plagas, la protección de cultivos de plagas reglamentadas mediante inspección y prevención, y asegurar que los productores cumplan requisitos fitosanitarios para mercados de destino a través de certificación y gestión del acceso de nuevos productos.
\\

\noindent El programa se estructura en torno a varios componentes clave, cada uno de los cuales contribuye al logro del resultado que persigue el programa:

\begin{enumerate}[label=\alph*.]  % Esto crea una lista numerada con letras
  \item \textbf{Problema identificado:} Los productores agrícolas no cuentan con condiciones fitosanitarias suficientes en la producción de productos vegetales y limitan el acceso al mercado.
  \item \textbf{Población objetivo:} Productos agrícolas.
  \item \textbf{Resultado específico:} Productos agrícolas cuentan con condiciones fitosanitarias para tener plantas y productos vegetales sanos en el mercado.
  \item \textbf{Sector:} Agrario.
  \item \textbf{Entidad responsable del PP:} Servicio Nacional de Sanidad Agraria (SENASA).
  \item \textbf{Niveles de gobierno que participan en la ejecución del PP:} Gobierno nacional, regional y local.
  \item \textbf{Otros componentes:}
    \begin{itemize}  % Lista con viñetas
      \item Diagnóstico y estudio de las plagas priorizadas: Se orienta en la toma y envío de muestras de cultivos y plagas priorizadas para estudiar e identificar el porcentaje de infestación en la calidad fitosanitaria.
      \item Acceso de nuevos productos a mercados internacionales: Aborda la gestión en la sanidad vegetal para lograr superar las barreras fitosanitarias establecidas por los países.
      \item Inspección y control de productos: Involucra un proceso de atención a todas las notificaciones por sospecha de plagas presentes en el producto.
    \end{itemize}
\end{enumerate}

\noindent El diseño del programa se basa en un enfoque integrado de actividades que implican capacitación, asistencia técnica, investigación, y difusión, para lograr un impacto sostenible en la gestión de los suelos agrarios.
\begin{center}
\textbf{\small GRÁFICO N° 01.} \\
\textbf{\small DISEÑO DEL PP 0040}
\end{center}
\vspace{-12pt}
\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{Resultado Especifico Productos y Actividades Diseño PP.jpg}
\end{figure}

\subsection{Indicadores de desempeño del programa presupuestal}

\noindent El programa cuenta con seis (7) indicadores de desempeño, de los cuales tres (3) indicadores son de resultado específico y cuatro (4) indicadores de producto. Estos indicadores miden las siguientes dimensiones:


\begin{center}
\textbf{\small TABLA N° 01.} \\
\textbf{\small INDICADORES DE DESEMPEÑO DEL PP 0040}
\end{center}
\vspace{-12pt}
\renewcommand{\arraystretch}{1.5}
\begin{longtable}{|p{7cm}|p{8.0cm}|}
\hline
\rowcolor[HTML]{538135} 
\multicolumn{2}{|c|}{\textcolor{white}{\textbf{Indicadores de Desempeño del PP 0040}}}
\endfirsthead
\multicolumn{2}{|c|}{\cellcolor[HTML]{A8D08D} \textbf{Resultado Específico}} \\ \hline
{\cellcolor[HTML]{E2EFD9}\textbf{Descripción del resultado específico}} & {\cellcolor[HTML]{E2EFD9}\textbf{Indicadores}} \\ \hline
\multirow{3}{7cm}{\raggedright Productores cuentan con condiciones fitosanitarias adecuadas para la producción y comercialización de plantas y productos vegetales y con acceso a mercados} 
& Reducción de las pérdidas anuales por la presencia de plagas en el país \\ \cline{2-2}
 & Índice de acceso fitosanitario a mercados internacionales \\ \cline{2-2}
 & Reducción de tasa de rechazos en planta empacadora \\ \hline

\multicolumn{2}{|c|}{\cellcolor[HTML]{A8D08D} \textbf{Productos}} \\ \hline
{\cellcolor[HTML]{E2EFD9}\textbf{Descripción del producto}} & {\cellcolor[HTML]{E2EFD9}\textbf{Indicadores}} \\ \hline
\multirow{3}{7cm}{Productores Agrícolas con Menor Presencia de Plagas Priorizadas} & Superficie libre de plagas declarada \\ \cline{2-2}
 & Reducción de la tasa de incidencia de plagas priorizadas \\ \hline
Productores Agrícolas con Cultivos Protegidos de la Introducción y Dispersión de Plagas Reglamentadas & Plaga reglamentada introducida \\ \hline
Productores con Capacidad Disponible para el Cumplimiento de Restricciones Fitosanitarias de los Mercados de Destino & Porcentaje de productores agrícolas con acceso a mercado \\ \hline

\end{longtable}



\subsection{Actores que intervienen en la ejecución del programa}

\noindent En la ejecución del Programa Presupuestal 0040 intervienen varios actores claves que operan a diferentes niveles de gobierno y sectores. Estos actores trabajan de manera conjunta para asegurar que las actividades del programa se desarrollen de manera eficiente y logren un impacto positivo en el mejoramiento y mantenimiento de la sanidad vegetal.

\begin{center}
\textbf{\small GRÁFICO N° 02.} \\
\textbf{\small ACTORES INTERVINIENTES DEL PP 0040}
\end{center}
\vspace{-10pt}
\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{diagrama de 2.4 reporte pp.jpg}
\end{figure}

\noindent Este enfoque colaborativo asegura que el programa se ejecute de manera eficiente, con un impacto significativo en la mejora de la sanidad vegetal y en el desarrollo del sector agrícola en el Perú.

\subsection{Evolución del presupuesto y de los indicadores del programa presupuestal}

\subsection*{a) Evolución del presupuesto del programa}

\noindent A nivel global, en el periodo del 2020 al 2024, el PP 0040 presenta una mejora constante desde el 2022, alcanzando su punto más alto en 2024 con un 97.0\%; asimismo, registra un incremento promedio anual del 2.7\% en el financiamiento global del programa. En 2020, el PIM fue de S/ 228.8 millones, con un monto devengado de S/ 218.1 millones y una ejecución del 95.3\%. El desempeño fue alto. En 2021, el PIM aumentó a S/ 258.9 millones, con un monto devengado de S/ 249.2 millones y una ejecución del 96.3\%. Como el presupuesto creció, el desempeño fue ligeramente mayor al año anterior, lo que sugiere que aún hubo espacio para mejorar el uso de los recursos. En 2022, el PIM ascendió a S/ 287.6 millones, con un monto devengado de S/ 274.0 millones y una ejecución del 95.3\%. Hubo una ligera caída en el desempeño. En 2023, el PIM se mantuvo en S/ 278.8 millones, con el monto devengado de S/ 269.2 millones, logrando una ejecución del 96.6\%, manteniendo un alto desempeño. Finalmente, en 2024, el PIM fue de S/ 249.9 millones, con un monto devengado de S/ 242.4 millones y una ejecución del 97.1\%, reflejando una mejora progresiva en los últimos 5 años. 

\begin{center}
\textbf{\small Gráfico N° 03} \\
\textbf{\small EVOLUCIÓN PRESUPUESTAL DEL PP 0040, 2020-2024} \\
\text{\small (En millones de soles)} % Título encima del gráfico en el formato solicitado
\end{center}
\vspace{-12pt}
\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{grafico1.png} % Reemplaza "grafico1.png" con el nombre de tu archivo
\end{figure}
\vspace{-25pt}
\begin{flushleft}
\footnotesize \hspace{1.3cm} \fontsize{9}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{flushleft}

\noindent A nivel nacional, entre los años 2020 y 2024, el gobierno nacional concentró el 78.9\% del presupuesto global del PP 0040, registrando una variación promedio anual del PIM del 1.1\%. En el 2022, presentó el PIM más alto de los últimos 5 años, que ascendió a S/ 224.7 millones. Por otro lado, en el 2024, el PIM alcanzó los S/ 193.3 millones, con un devengado de S/ 190.8 millones, presentando un desempeño de 98.7\%, el más alto de los últimos 5 años.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

\begin{center}
\textbf{\small Gráfico N° 04} \\
\textbf{\small EVOLUCIÓN PRESUPUESTAL DEL PP 40 A NIVEL NACIONAL, 2020-2024} \\
\text{\small (En millones de soles)} % Título encima del gráfico en el formato solicitado
\end{center}
\vspace{-12pt}
\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{grafico2.jpg} % Reemplaza "grafico2.png" con el nombre de tu archivo
\end{figure}
\vspace{-20pt}
\begin{flushleft}
\footnotesize \hspace{1.1cm} \fontsize{9}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{flushleft}
\noindent A nivel regional, entre los años 2020 y 2024, los gobiernos regionales concentraron el 12.5\% del presupuesto global del PP 0040, registrando un incremento promedio anual del PIM del 25.3\%. En el 2023, se presentó el PIM más alto de los últimos 5 años, que ascendió a S/ 32.3 millones. Por otro lado, en el 2020, el PIM alcanzó los S/ 11.5 millones, con un devengado de S/ 11.5 millones, presentando un desempeño de 99.2\%, el más alto de los últimos 5 años.  
\\\\\\\\\\\\\\\\\\\\\\\\\\

\begin{center}
\textbf{\small Gráfico N° 05} \\
\textbf{\small EVOLUCIÓN PRESUPUESTAL DEL PP 40 A NIVEL REGIONAL, 2020-2024} \\
\text{\small (En millones de soles)} % Título encima del gráfico en el formato solicitado
\end{center}
\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{grafico2.jpg} % Reemplaza "grafico2.png" con el nombre de tu archivo
\end{figure}
\begin{flushleft}
\footnotesize \hspace{1.1cm} \fontsize{9}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{flushleft}

\noindent A nivel local, entre los años 2020 y 2024, los gobiernos locales concentraron el 8.6\% del presupuesto global del PP 0040, registrando un incremento promedio anual del PIM del 2.9\%. En el 2022, se presentó el PIM más alto de los últimos 5 años, que ascendió a S/ 36.4 millones. Por otro lado, en el 2023, el PIM alcanzó los S/ 35.7 millones, con un devengado de S/ 32.7 millones, presentando un desempeño de 91.8\%, el más alto de los últimos 5 años.
\\\\\\\\\\\\\\\\\\


\begin{center}
\textbf{\small Gráfico N° 06} \\
\textbf{\small EVOLUCIÓN PRESUPUESTAL DEL PP 40 A NIVEL LOCAL, 2020-2024} \\
\text{\small (En millones de soles)} % Título encima del gráfico en el formato solicitado
\end{center}
\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{grafico2.jpg} % Reemplaza "grafico2.png" con el nombre de tu archivo
\end{figure}
\begin{flushleft}
\footnotesize \hspace{1.1cm} \fontsize{9}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{flushleft}

\section{Criterios y parámetros para el análisis del desempeño}

\noindent Los criterios empleados para evaluar el desempeño en la ejecución del Programa Presupuestal 0040 se han establecido con base en los porcentajes de progreso logrados en la ejecución financiera y física durante el primer semestre de 2024. Los parámetros definidos son los siguientes: \textbf{ALTO} (\( \geq \) 95\%), \textbf{REGULAR} (75\% - 95\%) y \textbf{BAJO} (\( < \) 75\%); como se detalla en la siguiente tabla: 
\begin{center}
\textbf{\small Tabla N° 02} \\
\textbf{\small CRITERIOS PARA LA EVALUACIÓN DE LA EJECUCIÓN FÍSICA Y FINANCIERA} \\
 % Título encima del gráfico en el formato solicitado
\end{center} 
\begin{table}[ht]
\centering
\begin{tabular}{|c|c|c|}
\hline
\rowcolor[HTML]{E7E6E6} 
\textbf{SEMÁFORO} & \textbf{CALIFICACIÓN} & \textbf{RANGO DE EJECUCIÓN} \\ \hline
\rowcolor[HTML]{A9D08E} 
\cellcolor[HTML]{A9D08E} \textcolor{black}{\textbf{Verde}} & \textbf{ALTO} & \textbf{$\geq$ 95\%} \\ \hline
\rowcolor[HTML]{FFEB9C} 
\cellcolor[HTML]{FFEB9C} \textcolor{black}{\textbf{Amarillo}} & \textbf{REGULAR} & \textbf{75\% - 95\%} \\ \hline
\rowcolor[HTML]{F4CCCC} 
\cellcolor[HTML]{F4CCCC} \textcolor{black}{\textbf{Rojo}} & \textbf{BAJO} & \textbf{< 75\%} \\ \hline
\end{tabular}
\begin{flushleft}
\scriptsize \hspace{0.9cm} \fontsize{8}{11}\selectfont \textbf{Fuente:} \text{Adaptado a la Guía para el Seguimiento y Evaluación de Políticas Nacionales y Planes del SINAPLAN.
}
\end{flushleft}
\end{table}
\\\\\\
\noindent Estos criterios se aplican a todas las áreas de análisis, lo que permite evaluar el rendimiento y detectar problemas cuando el progreso es menor al esperado.

\section{Análisis del desempeño en la ejecución del programa}

\noindent El análisis del desempeño en la ejecución del Programa Presupuestal 0040 se enfoca en revisar de qué manera se han cumplido las metas establecidas, tanto a nivel financiero como físico, durante el año 2024.


\subsection{Análisis del cumplimiento de metas financieras del programa}

\subsection*{\small{a) Asignación y ejecución presupuestal por niveles de gobierno}}

\noindent Al 31 de diciembre 2024, el PIM global del Programa Presupuestal 0040 asciende a S/ 249,910,373 de los cuales el Gobierno Nacional tiene S/ 193,312,208 con la participación de 77.4\%, el Gobierno Regional con S/ 24,541,354 tiene una participación del 9.8\%, y el Gobierno Local tiene S/ 32,056,811 con una participación del 12.8\%. 
\\

\noindent A su vez, la ejecución presupuestal global asciende a S/ 242,359,710 que representa el 97.0\% del PIM, registrando a nivel global un desempeño alto, según los criterios de evaluación
\\

\noindent El Gobierno Nacional con una ejecución de S/ 190,805,281 tiene un avance de 98.7\% logrando un desempeño alto; el Gobierno Local con una ejecución de S/ 27,709,789 tiene un avance de 86.4\% alcanzando un desempeño regular y el Gobierno Regional con un devengado de S/ 23,844,641 tiene una participación del 97.2\% alcanzando un desempeño alto.
\vspace{-0.1cm}

\begin{center}
\textbf{\small Tabla N° 03} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR NIVEL DE GOBIERNO AÑO 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-15pt}
\fontsize{11}{13}\selectfont
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{l c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{NIVEL DE GOBIERNO}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{GOBIERNO NACIONAL} & 174,441,019 & 193,312,208 & 77.4\% & 190,805,281 & 98.7\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{GOBIERNO LOCAL} & 28,411,400 & 32,056,811 & 12.8\% & 27,709,789 & 86.4\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{GOBIERNO REGIONAL} & 15,781,779 & 24,541,354 & 9.8\% & 23,844,641 & 97.2\% \\ 
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{249,910,373}} & \textcolor{white}{\textbf{100\%}} & \textcolor{white}{\textbf{242,359,710}} & \textcolor{white}{\textbf{97.0\%}} \\ 
\end{tabular}%
}
\vspace{-10pt}
\begin{flushleft}
\footnotesize \fontsize{8}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{flushleft}
\end{table}

\vspace{-20pt}
\subsection*{\small{b) Asignación y ejecución presupuestal por fuente de financiamiento}}

\noindent El PP 0040 se financia principalmente con Recursos Ordinarios con una participación del 64.3\% del PIM, seguida de Recursos Determinados con una participación del 20.8\% del PIM.
\\

\noindent Respecto a la ejecución presupuestal, solo la fuente de financiamiento Recursos Ordinarios alcanzó un desempeño alto, con una ejecución de S/ 159,954,907 que representa un avance del 99\% del PIM. Por el contrario, la fuente Donaciones y Transferencias presentó un desempeño bajo con un nivel de ejecución de 69.5\%.
\vspace{5pt}

\begin{center}
\textbf{\small Tabla N° 04} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR FUENTES DE FINANCIAMIENTO AÑO 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-15pt}
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{l c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{FUENTE DE FINANCIAMIENTO}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{1. RECURSOS ORDINARIOS (RO)} & 161,908,620 & 160,651,674 & 64.3\% & 159,954,907 & 99.6\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{2. RECURSOS DIRECTAMENTE RECAUDADOS (RDR)} & 2,361,489 & 1,537,034 & 0.6\% & 1,400,974 & 91.1\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{3. RECURSOS POR OPERACIONES OFICIALES DE CRÉDITO} & 13,461,616 & 34,608,754 & 13.8\% & 32,708,197 & 94.5\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{4. DONACIONES Y TRANSFERENCIAS (DYT)} & 15,000 & 1,050,550 & 0.4\% & 729,616 & 69.5\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{5. RECURSOS DETERMINADOS (RD)} & 40,887,473 & 52,062,361 &20.8\% & 47,566,015 & 91.4\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{249,910,373}} & \textcolor{white}{\textbf{100\%}} & \textcolor{white}{\textbf{242,359,710}} & \textcolor{white}{\textbf{97.0\%}} \\ 
\end{tabular}%
}
\vspace{-0.25cm}
\footnotesize \raggedright \fontsize{8}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{table}


\subsection*{\small{c) Asignación y ejecución presupuestal por genérica de gasto}}

\noindent El PP 0040 destinó el 51.7\% del PIM a Gasto Corriente, el cual presentó un desempeño alto con una ejecución del 99.3\%; mientras que el Gasto de Capital presentó un desempeño regular con una ejecución del 94.5\% del PIM.
\\

\noindent La genérica de gasto 5-21. Personal y Obligaciones Sociales, registró una participación de 22.1\% del PIM y una ejecución de S/ 54,873,744 que representa un avance del 99.5\%, obteniendo un desempeño alto. Esta categoría comprende, el financiamiento de los gastos por retribuciones y complementos de cargas sociales adjudicados al personal activo con vínculo laboral, así como gastos para las contribuciones a la seguridad social, profesionales de los sectores involucrados y relacionados con la entrega de los productos del programa presupuestal.
\\

\noindent A su vez, la genérica de gasto 5-23. Bienes y Servicios, registró una participación del 29.3\% del PIM y una ejecución de S/ 72,530,623 que representa un avance del 99.1\%, obteniendo un desempeño alto. Esta genérica de gasto comprende dos sub-genéricas: compra de bienes y contratación de servicios.
\\

\noindent Por su parte la genérica 5-25. Otros Gastos, con un PIM de S/ 723,942, registró una participación de 0.3\% del PIM y una ejecución de S/ 723,633 que representa el 100\% del PIM, alcanzado un  desempeño alto. Esta genérica comprende gastos por subsidios a empresas públicas y privadas del país que persiguen fines productivos, transferencias distintas a donaciones, subvenciones a personas naturales, pago de impuestos, derechos administrativos, multas gubernamentales y sentencias judiciales. Asimismo, incluye gastos definidos para la negociación colectiva en el marco de la Ley Nº 31188.
\\

\noindent La genérica de gasto 6-26 Adquisición de Activos No Financieros, con un PIM de S/ 120,601,561 concentró el 48.3\% del PIM y registró una ejecución de S/ 113,992,029 que representa un avance del 94.5\%, obteniendo un desempeño regular. Esta genérica comprende la construcción de edificios y estructuras, vehículos, maquinaria, así como inversiones intangibles y otros gastos de activos no financieros como elaboración de expedientes técnicos, estudios de pre-inversión, entre otros. La genérica de gasto 6-24 Donaciones y Transferencias tiene una ejecución del 100.0\% con un PIM de S/ 23,565.


\begin{center}
\textbf{\small Tabla N° 05} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR FUENTES DE FINANCIAMIENTO, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-15pt}

\fontsize{11}{13}\selectfont
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{l c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{GENÉRICA DE GASTO}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{5-21. PERSONAL Y OBLIGACIONES SOCIALES} & 58,861,705 & 55,148,716  & 22.1\% & 54,873,744 & 99.5\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{5-22. PENSIONES Y OTRAS PRESTACIONES SOCIALES} & 0 & 8,180 & 0\% & 8,170 & 99.9\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{5-23. BIENES Y SERVICIOS} & 75,176,133 & 73,196,461 & 29.3\% & 72,530,623 & 99.1\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{5-24. DONACIONES Y TRANSFERENCIAS} & 234,781 & 207,948 & 0.1\% & 207,948 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{5-25 OTROS GASTOS} & 1,222,695 & 723,942 & 0.3\% & 723,633 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{6.24. DONACIONES Y TRANSFERENCIAS} & 0 & 23,565 & 0.0\% & 23,565 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{6-26. ADQUISICIÓN DE ACTIVOS NO FINANCIEROS} & 83,138,884 & 120,601,561 & 48.3\% & 113,992,029 & 94.5\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{100.0\%}} & \textcolor{white}{\textbf{249,910,373}} & \textcolor{white}{\textbf{97.0\%}} \\ 
\end{tabular}%
}

\footnotesize \raggedright \fontsize{8}{11}\selectfont \vspace{0.2cm} \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{table}
\vspace{0.5cm}
\subsection*{\small{d) Asignación y ejecución presupuestal por tipo de intervención}}

\noindent El presupuesto asignado para las intervenciones del PP 0040 se distribuyó en productos y proyectos. Los productos, que representan el 51.9\% del PIM, alcanzaron una ejecución del 99.2\%, lo que refleja un desempeño alto. En contraste, los proyectos, con una participación del 48.1\% del PIM, lograron una ejecución del 94.5\%, registrando un desempeño regular, tal como se detalla en la siguiente tabla:
\vspace{-0.2cm}

\begin{center}
\textbf{\small TABLA N° 06} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR TIPO DE INTERVENCIÓN, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-15pt}
\fontsize{11}{13}\selectfont
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{l c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / PROYECTO}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{PROYECTO} & 83,050,644 & 120,161,217 & 48.1\% & 113,586,428 & 94.5\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{PRODUCTO} & 135,583,554 & 129,749,156 & 51.9\% & 128,773,283 & 99.2\% \\ 
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{249,910,373}} & \textcolor{white}{\textbf{100\%}} & \textcolor{white}{\textbf{242,359,710}} & \textcolor{white}{\textbf{97.0\%}} \\ 
\end{tabular}%
}

\footnotesize \raggedright \fontsize{8}{11}\selectfont \vspace{0.2cm} \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{table}

\vspace{-0.6cm}
\subsection*{\small{e)	Asignación y ejecución presupuestal por producto y actividad}}

\noindent El análisis en la ejecución del PP 0040, a nivel de metas financieras por productos y actividades muestra:
\\\\
\underline{\textbf{Producto 3000380 Productores agrícolas con menor presencia de plagas priorizadas}}

\begin{itemize}
    \item \textbf{Actividad 5000189 “Control y/o Erradicación de Plagas Priorizadas”} esta actividad garantiza la eficaz y eficiente implementación de acciones de prevención (capacitación y sensibilización de productores) y de control y/o erradicación de plagas mediante el Manejo Integrado de Plagas (control cultural, químico, mecánico, biológico, etc.).
    En el 2024, se registró un avance del 98.8\% con una ejecución financiera de S/ 59,152,421 de un PIM de S/ 59,856,077 que refleja un desempeño es alto.
    \item \textbf{Actividad 5001308 “Vigilancia Fitosanitaria de Plagas Presentes”} ” comprende un grupo de actividades oficiales, tales como la prospección, evaluación, monitoreo, y otros procedimientos, a través de los cuales se recoge y registra información sobre la presencia o ausencia de una plaga.
    En el 2024, se registró un avance del 99.4\% con una ejecución financiera de S/ 18,562,799 de un PIM de S/ 18,680,297 que refleja un desempeño es alto.
    \item \textbf{Actividad 5000200 “Diagnóstico de Plagas de Productos Vegetales”} esta actividad consiste en la toma y envío de muestras de cultivos y plagas priorizados a la Unidad del Centro de Diagnóstico de Sanidad Vegetal (UCDSV), siguiendo protocolos especiales.
    En el 2024, se ejecutó S/ 18,562,799 de un PIM de S/ 18,680,297 alcanzando un desempeño alto.
\end{itemize}

\\\\
\noindent \underline{\textbf{Producto 3000525 Productores Agrícolas con Cultivos Protegidos de la Introducción}}
\vspace{0.15cm}
\\  \underline{\textbf{y Dispersión de Plagas Reglamentarias}}

\begin{itemize}
    \item \textbf{Actividad 5000201 “Diagnóstico de Plagas de Productos Vegetales Importados”} implica la remisión de muestras vegetales por parte de los inspectores de los Puestos de Control Cuarentenario (PCC) y redes de monitoreo. Estas muestras son enviadas al Centro de Diagnóstico de Sanidad Vegetal y, tras cumplir con los protocolos establecidos, se analizan en los laboratorios correspondientes. Los resultados del análisis se entregan en un rango de 3 a 21 días, dependiendo del método de ensayo y tipo de análisis utilizado. Además, incluye el fortalecimiento de capacidades técnicas para mejorar el diagnóstico y desarrollar nuevos métodos mediante técnicas moleculares.
    En el 2024, registró una ejecución financiera de S/ 721,803 de un PIM de S/ 721,828 que refleja un desempeño es alto.
    \item \textbf{Actividad 5000297 “Inspección y Control de Ingresos de Plantas, Productos Vegetales y Otros”} permite prevenir el ingreso de plagas mediante el Análisis de Riesgo de Plagas (ARP), el cual evalúa evidencias biológicas, científicas y económicas para determinar si una plaga debe ser reglamentada y la intensidad de las medidas fitosanitarias a adoptar. Este análisis, a su vez, facilita el establecimiento de requisitos fitosanitarios para la importación de productos, con el objetivo de minimizar el riesgo de ingreso y establecimiento de plagas. Los estudios se aplican a productos en la Categoría de Riesgo Fitosanitario (CRF) y los requisitos establecidos se publican en normas oficiales.
    En el 2024, registró una ejecución de S/ 12,611,480 de un PIM de S/ 12,624,813, logrando un desempeño es alto.
    \item \textbf{Actividad 5001309 “Vigilancia Fitosanitaria Preventiva de Plagas No Presentes”} se centra en monitorear áreas específicas en busca de plagas que aún no se han detectado, pero que podrían ingresar a una región debido al comercio internacional o a condiciones ambientales favorables. A través de la implementación de redes de vigilancia, que incluyen trampas, muestreo de vegetación y análisis en laboratorios, se recopilan datos sobre la posible presencia de estas plagas. El objetivo es detectar su llegada en fases tempranas, lo que permite tomar medidas de control antes de que se conviertan en una amenaza significativa. Esta vigilancia contribuye a reducir el riesgo de invasión de plagas, protegiendo así la biodiversidad local y la producción agrícola.
    En el 2024, registró una ejecución financiera de S/ 25,619,412 de un PIM de S/ 25,633,499 que refleja un desempeño es alto.
\end{itemize}

\noindent \underline{\textbf{Producto 3000526 Productores con Capacidad Disponible para el Cumplimiento}}
\vspace{0.15cm}
\\  \underline{\textbf{de Restricciones Fitosanitarias de los Mercados de Destino}}

\begin{itemize}
    \item \textbf{Actividad 5000183 “Certificación Fitosanitaria”} comprende procedimientos fitosanitarios para certificar plantas, productos vegetales y otros artículos reglamentados, que incluyen la inspección de lugares de producción, plantas de tratamiento, y la ejecución de tratamientos cuarentenarios. Si se cumplen las regulaciones, se emite un Certificado Fitosanitario; de lo contrario, el envío es rechazado, impidiendo la exportación.
    En el 2024, registró una ejecución financiera de S/ 8,525,749 de un PIM de S/ 8,649,774 que refleja un desempeño es alto. Esto sugiere que no hay problemas de ejecución relacionados con la planificación, asignación de recursos o desafíos técnicos.
    \item \textbf{Actividad 5003090 “Gestión de Acceso de Nuevos Productos a Mercados Internacionales”} comprende la negociación técnica sobre la propuesta de requisitos fitosanitarios, elaborar y gestionar información sobre plagas para el acceso del producto, evaluar las zonas de producción con técnicos del mercado de destino, la conformidad de los requisitos fitosanitarios establecidos por el país de destino.
    En el 2024, registró una ejecución financiera de S/ 1,380,732 de un PIM de S/ 1,383,875 que refleja un desempeño es alto. Esto sugiere que no hay problemas de ejecución relacionados con la planificación, asignación de recursos o desafíos técnicos.
\end{itemize}

\vspace{-0.5cm}

\begin{center}
\textbf{\small TABLA N° 07} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR PRODUCTO Y ACTIVIDAD, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-0.8cm}
\fontsize{11}{13}\selectfont
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{m{7.5cm} c c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / ACTIVIDAD}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{E7E6E6} 
\raggedright \textbf{3000380. PRODUCTORES AGRÍCOLAS CON MENOR PRESENCIA DE PLAGAS PRIORIZADAS} & 95,926,990 & 80,735,367  & 70.8\% & 79,914,106 & \rowcolor[HTML]{63BE7B} 99.0\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{5000189. CONTROL Y/O ERRADICACION DE PLAGAS PRIORIZADAS} & 34,600,879 & 18,680,297 & 25.5\% & 18,562,799 & 99.4\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{5001308. VIGILANCIA FITOSANITARIA DE PLAGAS PRESENTES} & 1,901,520 & 2,198,993 & 29.3\% & 72,530,623 & 99.1\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{3000525. PRODUCTORES AGRÍCOLAS CON CULTIVOS PROTEGIDOS DE LA INTRODUCCIÓN Y DISPERSIÓN DE PLAGAS REGLAMENTADAS} & 234,781 & 207,948 & 0.1\% & 207,948 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{5000201. DIAGNOSTICO DE PLAGAS DE PRODUCTOS VEGETALES IMPORTADOS} & 1,222,695 & 723,942 & 0.3\% & 723,633 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{5000297. INSPECCION Y CONTROL DEL INGRESO DE PLANTAS, PRODUCTOS VEGETALES Y OTROS ARTICULOS REGLAMENTADOS} & 0 & 23,565 & 0.0\% & 23,565 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{5001309. VIGILANCIA FITOSANITARIA PREVENTIVA DE PLAGAS NO PRESENTES} & 83,138,884 & 120,601,561 & 48.3\% & 113,992,029 & 94.5\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{100.0\%}} & \textcolor{white}{\textbf{249,910,373}} & \textcolor{white}{\textbf{97.0\%}} \\ 
\end{tabular}%
}

\vspace{-1pt}
\footnotesize \raggedright \fontsize{8}{11}\selectfont \vspace{0.2cm} \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{table}

\vspace{-15pt}
\subsection*{\small{f) Asignación y ejecución presupuestal por departamento}}

\noindent El PP 0040 destina más del 50.0\% del PIM a los departamentos de Cusco, Piura, Lima e Ica; mientras que, Madre de Dios, Huancavelica y Ucayali presentan la menor participación en la asignación de recursos.
\\

\noindent En cuanto al nivel de ejecución, 21 departamentos y la Provincia Constitucional del Callao lograron un desempeño alto, donde destacan Madre de Dios, Tacna y Provincia Constitucional del Callao; mientras que, 2 departamentos obtuvieron un desempeño regular y solo Apurímac presentó un desempeño bajo.

\vspace{5cm}
\begin{center}
\textbf{\small TABLA N° 08} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR DEPARTAMENTO, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-0.8cm}
\fontsize{9}{11}\selectfont
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{m{7.5cm} c c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{DEPARTAMENTO}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{01: AMAZONAS} & 13,596,158 & 9,739,714  & 3.9\% & 9,046,299 & \rowcolor[HTML]{FFEF9C} 92.9\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{02: ANCASH} & 5,252,695 & 6,976,893 & 2.8\% & 6,608,101 & \rowcolor[HTML]{FFEF9C} 94.7\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{03: APURIMAC} & 6,514,344 & 6,738,729 & 2.7\% & 5,177,293 & \rowcolor[HTML]{F8696B} 76.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{04: AREQUIPA} & 9,121,804 & 10,254,204 & 4.1\% & 10,211,59 & \rowcolor[HTML]{63BE7B} 99.6\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{06: CAJAMARCA} & 8,154,884 & 7,498,349 & 3.0\% & 7,440,995 & \rowcolor[HTML]{63BE7B} 99.2\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{07: CALLAO} & 14,311,241 & 13,918,705 & 5.6\% & 13,916,828 & \rowcolor[HTML]{63BE7B} 99.9\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{08: CUSCO} & 33,260,041 & 49,781,018 & 19.9\% & 47,804,767 & \rowcolor[HTML]{63BE7B} 96.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{09: HUANCAVELICA} & 1,716,398 & 1,114,594 & 0.4\% & 1,101,720 & \rowcolor[HTML]{63BE7B} 98.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{10: HUANUCO} & 1,965,476 & 1,714,915 & 0.7\% & 1,645,557 & \rowcolor[HTML]{63BE7B} 96.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textbf{11: ICA} & 11,893,564 & 13,634,019 & 5.5\% & 13,583,438 & \rowcolor[HTML]{63BE7B} 99.6\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{12: JUNIN} & 2,288,414 & 2,063,288 & 0.8\% & 2,056,884 & \rowcolor[HTML]{63BE7B} 99.7\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{13: LA LIBERTAD} & 11,426,513 & 12,573,743 & 5.0\% & 12,287,226 & \rowcolor[HTML]{63BE7B} 97.7\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{14: LAMBAYEQUE} & 8,514,350 & 11,048,528 & 4.4\% & 11,023,514 & \rowcolor[HTML]{63BE7B} 99.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{15: LIMA} & 21,551,857 & 24,969,881 & 10.0\% & 24,285,466 & \rowcolor[HTML]{63BE7B} 97.3\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{16: LORETO} & 1,792,390 & 1,331,954 & 0.5\% & 1,324,498 & \rowcolor[HTML]{63BE7B} 99.4\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{17: MADRE DE DIOS} & 5,303,724 & 974,476 & 0.4\% & 973,285 & \rowcolor[HTML]{63BE7B} 99.9\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{18: MOQUEGUA} & 5,820,000 & 6,769,244 & 2.7\% & 6,756,418 & \rowcolor[HTML]{63BE7B} 99.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{19: PASCO} & 1,197,086 & 1,027,573 & 0.4\% & 1,025,092 & \rowcolor[HTML]{63BE7B} 99.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{20: PIURA} & 18,417,034 & 41,258,234 & 16.5\% & 40,219,747 & \rowcolor[HTML]{63BE7B} 97.5\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{21: PUNO} & 11,293,184 & 6,103,559 & 2.4\% & 5,724,242 & \rowcolor[HTML]{FFEF9C} 93.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{22: SAN MARTIN} & 3,657,600 & 2,605,963 & 1.0\% & 2,495,105 & \rowcolor[HTML]{63BE7B} 95.7\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{23: TACNA} & 7,192,131 & 7,278,102 & 2.9\% & 7,274,441 & \rowcolor[HTML]{63BE7B} 99.9\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{24: TUMBES} & 10,652,615 & 5,788,658 & 2.3\% & 5,764,785 & \rowcolor[HTML]{63BE7B} 99.6\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  \textbf{25: UCAYALI} & 446,177 & 1,118,496 & 0.4\% & 1,108,441 & \rowcolor[HTML]{63BE7B} 99.1\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{218,634,198}} & \textcolor{white}{\textbf{249,910,373}} & \textcolor{white}{\textbf{100.0\%}} & \textcolor{white}{\textbf{242,359,710}} & \textcolor{white}{\textbf{97.0\%}} \\ 
\end{tabular}%
}

\footnotesize \raggedright \fontsize{8}{11}\selectfont \vspace{0.2cm} \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{table}
\vspace{-10pt}
\subsection{Análisis sectorial del cumplimiento de metas financieras}

\subsection*{\small{a) Asignación y ejecución presupuestal por tipo de intervención, según Pliego y Unidad Ejecutora}}

\noindent \fontsize{11}{13}\selectfont{En esta sección se analiza el desempeño del Sector Agrario y de Riego en la implementación del Programa a través de actividades y proyectos. Cabe indicar que el único pliego del sector que participa en la implementación del PP 0040 es SENASA, mediante las unidades ejecutoras de SENASA y PRODESA.}

\noindent La unidad ejecutora SENASA, registró un nivel de ejecución del 99.8\% a nivel de productos y un nivel de ejecución de 100.0\% a nivel de proyectos. Mientras que, PRODESA reportó un desempeño alto en la ejecución presupuestal, con un porcentaje de ejecución del 96.7\% destinado únicamente a inversiones. 

\begin{center}
\textbf{\small Tabla N° 11} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL POR EJECUTORAS, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-15pt}
\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{l c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{EJECUTORAS/TIPO DE INTERVENCIÓN}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\rowcolor[HTML]{E7E6E6}
\raggedright \textbf{PRODESA} & \textbf{45,677,478} & \textbf{67,355,575} & \textbf{34.8\%} & \textbf{65,145,380} & \textbf{96.7\%} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textcolor[HTML]{44546A}{\textit{Proyecto}} & 45,677,478 & 67,355,575 & 34.8\% & 65,145,380 & 96.7\% \\ 
\rowcolor[HTML]{E7E6E6}
\raggedright  \textbf{SENASA} & \textbf{128,763,541} & \textbf{125,956,633} & \textbf{65.2\%} & \textbf{125,659,901} & \textbf{99.8\%} \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \textcolor[HTML]{44546A}{\textit{Actividades}} & 128,763,541 & 124,527,374 & 64.4\% & 124,230,868 & 99.8\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright \textcolor[HTML]{44546A}{\textit{Proyecto}} & 0 & 1,429,259 & 0.7\% & 1,429,033 & 100.0\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{174,441,019}} & \textcolor{white}{\textbf{193,312,208}} & \textcolor{white}{\textbf{100.0\%}} & \textcolor{white}{\textbf{190,805,281}} & \textcolor{white}{\textbf{98.7\%}} \\ 
\end{tabular}%
}

\vspace{0.1cm} \footnotesize \raggedright \fontsize{8}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\end{table}

\vspace{-10pt}
\subsection*{\small {b) Asignación y Ejecución Presupuestal por Producto y Actividad, según Ejecutora}}

\noindent En el PP 0040 participa solo una unidad ejecutora en la ejecución de productos y actividades: la Unidad Ejecutora de Administración Central del SENASA.
\\

\noindent La Administración Central del SENASA destina su presupuesto a los productos presupuestales: “Productores Agrícolas con Menor Presencia de Plagas Priorizadas”, “Productores Agrícolas con Cultivos Protegidos de la Introducción y Dispersión de Plagas Reglamentadas” y “Productores con Capacidad Disponible para el Cumplimiento con Restricciones Fitosanitarias de los Mercados de Destino”. El primer producto cuenta con un PIM de S/ 75,513,585 y una ejecución de S/75,371,691 que representa un avance de 99.8\%. El segundo producto cuenta con un PIM de S/ 38,980,184, de los cuales ha ejecutado S/ 38,952,695 que representan un 99.9\% de avance, obteniendo un desempeño alto en el año 2024. El último producto cuenta con un PIM de S/ 10,033,649 y una ejecución de S/ 9,906,482, que registran un avance de 98.7\%. 
\vspace{-0.1cm}

\begin{center}
\textbf{\small TABLA N° 12} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL DE LAS ACTIVIDADES A NIVEL DE EJECUTORAS, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-0.6cm}
\fontsize{9}{9.5}\selectfont
\setlength{\extrarowheight}{2pt} % opcional para darle espacio vertical a las filas

\begin{tabularx}{\textwidth}{
  >{\raggedright\arraybackslash}X
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.0cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.5cm}
}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / ACTIVIDAD}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE\%}} \\
\endfirsthead
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / ACTIVIDAD}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\
\endfirsthead
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / ACTIVIDAD}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\
\endhead
\rowcolor[HTML]{E2EFD9} 
\raggedright \textbf{160. SENASA} & 128,763,541 & 124,527,374  & 100.0\% & 124,230,867 & \rowcolor[HTML]{63BE7B} 99.8\% \\ 
\rowcolor[HTML]{EDEDED} 
\raggedright \textbf{SENASA} & 128,763,541 & 124,527,374  & 100.0\% & 124,230,867 & \rowcolor[HTML]{63BE7B} 99.8\% \\ 
\rowcolor[HTML]{E7E6E6} 
\raggedright \textbf{3000380. PRODUCTORES AGRÍCOLAS CON MENOR PRESENCIA DE PLAGAS PRIORIZADAS} & 89,106,977 & 75,513,585  & 60.7\% & 75,371,691 & \rowcolor[HTML]{63BE7B} 99.8\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright  {5000189. CONTROL Y/O ERRADICACION DE PLAGAS PRIORIZADAS} & 52,604,578 & 54,634,295 & 43.9\% & 54,610,006 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  {5000200. DIAGNÓSTICO DE PLAGAS DE PRODUCTOS VEGETALES} & 1,901,520 & 2,198,993 & 1.8\% & 2,198,886 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright  {5001308. VIGILANCIA FITOSANITARIA DE PLAGAS PRESENTES} & 34,600,879 & 18,680,297 & 15.0\% & 18,562,799 & 99.4\% \\
\rowcolor[HTML]{E7E6E6}
\raggedright \textbf{3000525. PRODUCTORES AGRÍCOLAS CON CULTIVOS PROTEGIDOS DE LA INTRODUCCIÓN Y DISPERSIÓN DE PLAGAS REGLAMENTADAS} & 29,705,123 & 38,980,140 & 31.3\% & 38,952,695 & 99.9\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {5000201. DIAGNOSTICO DE PLAGAS DE PRODUCTOS VEGETALES IMPORTADOS} & 939,894 & 721,828 & 0.6\% & 721,803 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {5000297. INSPECCION Y CONTROL DEL INGRESO DE PLANTAS, PRODUCTOS VEGETALES Y OTROS ARTICULOS REGLAMENTADOS} & 12,541,172 & 12,624,813 & 10.1\% & 12,611,480 & 99.9\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {5001309. VIGILANCIA FITOSANITARIA PREVENTIVA DE PLAGAS NO PRESENTES} & 16,224,057 & 25,633,499 & 20.6\% & 25,619,412 & 99.9\% \\
\rowcolor[HTML]{E7E6E6} 
\raggedright \textbf{3000526.PRODUCTORES CON CAPACIDAD DISPONIBLE PARA EL CUMPLIMIENTO DE RESTRICCIONES FITOSANITARIAS DE LOS MERCADOS DE DESTINO} & 9,951,441 & 10,033,649 & 8.1\% & 9,906,481 & 98.7\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {5000183. CERTIFICACIÓN FITOSANITARIA} & 8,851,066 & 8,649,774 & 6.9\% & 8,525,749 & 98.6\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {5003090. GESTIÓN DE ACCESO DE NUEVOS PRODUCTOS A MERCADOS INTERNACIONALES} & 1,100,375 & 1,383,875  & 1.1\% & 1,380,732 & 99.8\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{128,763,541}} & \textcolor{white}{\textbf{124,527,374}} & \textcolor{white}{\textbf{100.0\%}} & \textcolor{white}{\textbf{124,230,867}} & \textcolor{white}{\textbf{99.8\%}} \\ 
\end{tabularx}

\vspace{-0.3cm} \footnotesize \raggedright \fontsize{8}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}

\vspace{-0.1cm} \subsection*{\small {c) Asignación y Ejecución Presupuestal por proyecto, según Unidad Ejecutora}}

\fontsize{11}{13}\selectfont \begin{justify}{
\noindent El pliego SENASA ejecutó durante el 2024, 5 inversiones a través de sus unidades ejecutoras SENASA y PRODESA. \\

\noindent SENASA ejecutó 3 IOAAR que concentraron el 2.1\% del PIM destinado a inversiones, registrando un nivel de ejecución promedio de 100.0\%. Estas inversiones involucraron la adquisiciones de equipamiento para control biológico en la región Lima con el objetivo de contribuir con el cierre de brechas en la capacidad operativa.
\\

\noindent Por su parte, PRODESA ejecutó 2 proyectos de inversión que concentraron el 97.9\% del PIM registrando un avance promedio de 96.7\%. Estas inversiones estuvieron vinculadas a la gestión de la unidad ejecutora y la erradicación de la mosca de la fruta en los departamentos de Piura, Tumbes, Lambayeque, La Libertad, Cajamarca, Amazonas, Apurímac, Cusco y Puno.}
\end{justify}

\begin{center}
\textbf{\small Tabla N° 13} \\
\textbf{\small EJECUCIÓN PRESUPUESTAL DE LAS ACTIVIDADES A NIVEL DE EJECUTORAS, 2024} \\
 % Título encima del gráfico en el formato solicitado
\text{\small (En soles)} 
\end{center}
\vspace{-0.5cm}
\fontsize{9}{9.5}\selectfont
\begin{tabularx}{\textwidth}{
  >{\raggedright\arraybackslash}X
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.0cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.5cm}
}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PROYECTOS}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE\%}} \\
\endfirsthead
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PROYECTOS}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\
\endfirsthead
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PROYECTOS}} & \textcolor{white}{\textbf{PIA}} & \textcolor{white}{\textbf{PIM}} & \textcolor{white}{\textbf{PART\%}} & \textcolor{white}{\textbf{EJECUCIÓN}} & \textcolor{white}{\textbf{AVANCE \%}} \\
\endhead
\rowcolor[HTML]{E7E6E6} 
\raggedright \textbf{PRODESA} & 45,677,478 & 67,355,575  & 97.9\% & 65,145,380 & \rowcolor[HTML]{63BE7B} 96.7\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {2340924: GESTIÓN DEL PROGRAMA Y OTROS: PROGRAMA DE DESARROLLO DE LA SANIDAD AGRARIA Y LA INOCUIDAD AGROALIMENTARIA FASE II} & 1,935,260 & 3,092,560 & 4.5\% & 3,001,647 & 97.1\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {2343984: ERRADICACIÓN DE LA MOSCA DE LA FRUTA EN LOS DEPARTAMENTOS DE PIURA, TUMBES, LAMBAYEQUE, LA LIBERTAD, CAJAMARCA, AMAZONAS, APURÍMAC, CUSCO Y PUNO} & 43,742,218 & 64,263,015 & 93.4\% & 62,143,733 & 96.7\% \\
\rowcolor[HTML]{E7E6E6} 
\raggedright \textbf{SENASA} & 0 & 1,429,259  & 2.1\% & 1,429,033 & \rowcolor[HTML]{63BE7B} 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {2654833: ADQUISICION DE COMPUTADORA (TELEMEDICINA); EN EL(LA) UNIDAD DE INFORMATICA Y ESTADISTICA EN EL CENTRO POBLADO LA MOLINA, DISTRITO DE LA MOLINA, PROVINCIA LIMA, DEPARTAMENTO LIMA} & 0 & 1,090,826 & 1.6\% & 1,090,825 & 100.0\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {2659744: ADQUISICIÓN DE AUTOCLAVE, REFRIGERADORA (INS), CABINA DE SEGURIDAD BIOLÓGICA - CAMARA DE BIOSEGURIDAD Y MICROSCOPIO (OTROS); ADEMÁS DE OTROS ACTIVOS EN EL(LA) DIRECCIÓN DE SANIDAD VEGETAL - LABORATORIO DE CUARENTENA DE LA SUBDIRECCION DE CONTROL BIOLÓGICO EN EL CENTRO POBLADO VITARTE, DISTRITO DE ATE, PROVINCIA LIMA, DEPARTAMENTO LIMA} & 0 & 184,431 & 0.3\% & 184,208 & 99.9\% \\
\rowcolor[HTML]{FFFFFF} 
\raggedright {2660877: ADQUISICION DE MESA TECNICA PARA LABORATORIO, MESA TÉCNICA PARA LABORATORIO, MESA TÉCNICA PARA LABORATORIO Y IMPRESORA MULTIFUNCIONAL; ADEMAS DE OTROS ACTIVOS EN EL(LA) DIRECCION EJECUTIVA LIMA Y CALLAO - DELYC EN EL CENTRO POBLADO VITARTE, DISTRITO DE ATE, PROVINCIA LIMA, DEPARTAMENTO LIMA} & 0 & 154,002 & 0.2\% & 154,000 & 100.0\% \\
\rowcolor[HTML]{538135} 
\textcolor{white}{\raggedright \textbf{Total}} & \textcolor{white}{\textbf{45,677,478}} & \textcolor{white}{\textbf{68,784,834}} & \textcolor{white}{\textbf{100.0\%}} & \textcolor{white}{\textbf{66,574,413}} & \textcolor{white}{\textbf{96.8\%}} \\ 
\end{tabularx}

\vspace{-0.3cm}
\footnotesize \raggedright \fontsize{8}{11}\selectfont \textbf{Fuente:} \text{Consulta Amigable SIAF al 31/12/2024}
\subsection{Análisis del cumplimiento de metas físicas del programa}

\subsection*{\small{a) Ejecución fisica por producto y actividad}}

\noindent \fontsize{11}{13}\selectfont \begin{justify}{El análisis del desempeño en la ejecución de metas físicas del PP 0040, se enfoca en el cumplimiento de metas a nivel de actividades y productos presupuestales en el 2024. \\

\noindent \underline{\textbf{Producto 3000380 Productores Agrícolas con Menor Presencia de Plagas}}\\\\
\noindent Este producto presupuestal logró beneficiar a 362,565 productores a través del desarrollo de las siguientes actividades presupuestales: \\
\vspace{-0.15cm}
\begin{itemize}
    \item \textbf{Actividad 5000189 “Control y/o Erradicación de Plagas Priorizadas”}\\
    Durante el 2024, se ha logrado el control y/o erradicación de plagas priorizadas en 506,444 hectáreas mediante el Manejo Integrado de Plagas (control cultural, químico, mecánico, biológico, etc.), registrando un nivel de cumplimiento del 122.8\% de la meta programada (412,384 hectáreas), obteniendo un desempeño alto.
    \item \textbf{Actividad 5001308 “Vigilancia Fitosanitaria de Plagas Presentes”} \\
    En el periodo 2024, se implementó el proceso de vigilancia en 2,454,379 hectáreas superando la meta programada (2,425,100 hectáreas) obteniendo un desempeño alto. Esto gracias a la notificación oportuna de ocurrencia de plagas por parte de los agricultores y entidades locales.
    \item \textbf{Actividad 5000200 “Diagnóstico de Plagas de Productos Vegetales”} \\
    En el año 2024, se ejecutó 18,564 diagnósticos de plagas en productos vegetales a demanda de usuarios a través de la UCDSV, registrando un nivel de ejecución de 101.2\% respecto a la meta programada (18,225 diagnósticos), obteniendo un desempeño alto.\\
\end{itemize}

\noindent \underline{\textbf{Producto 3000525 Productores Agrícolas con Cultivos Protegidos de la Introducción}} 
\vspace{0.15cm}
\\  \underline{\textbf{y Dispersión de Plagas Reglamentarias}} \\

\noindent Este producto presupuestal logró beneficiar a 2,301,739 productores a través del desarrollo de las siguientes actividades presupuestales: \\
\vspace{-0.15cm}
\begin{itemize}
    \item \textbf{Actividad 5000201 “Diagnóstico de Plagas de Productos Vegetales Importados”}\\
    En el periodo 2024, se han elaborado 16,174 diagnósticos de plagas en productos vegetales importados a través de los laboratorios de la UCDSV, obteniendo un nivel de ejecución del 154.9\% respecto a la meta programada de 10,440 diagnósticos, obteniendo un desempeño alto.
    \item \textbf{Actividad 5000297 “Inspección y Control de Ingresos de Plantas, Productos Vegetales y Otros”} \\
    En el marco de esta actividad, se han elaborado 3,733,768 dictámenes de inspección y control de ingresos de planta, productos vegetales, logrando un nivel de ejecución del 186.4\% de la meta programada de 2,002,252, registrando un desempeño alto.
    \item \textbf{Actividad 5001309 “Vigilancia Fitosanitaria Preventiva de Plagas No Presentes” } \\
    En el año 2024, se ha gestionado la vigilancia fitosanitaria preventiva de plagas no presentes en 294,255 hectáreas a fin de alertar oportunamente la incursión de plagas no presentes como fusarium en banano, cancro en cítricos, las cuales fueron contenidas. Este resultado representa una ejecución del 153.6\% respecto a la meta programada de 191,538 hectáreas, obteniendo un desempeño alto.\\
\end{itemize}
\\

\noindent \underline{\textbf{Producto 3000526 Productores con Capacidad Disponible para el Cumplimiento }}
\vspace{0.15cm}
\\  \underline{\textbf{de Restricciones Fitosanitarias de los Mercados de Destino}} \\

\noindent Este producto logró beneficiar a 18,626 productores a través del desarrollo de las siguientes actividades presupuestales: \\
\vspace{-0.15cm}
\begin{itemize}
    \item \textbf{Actividad 5000183 “Certificación Fitosanitaria”}\\
    Durante el 2024, se han certificado 191,401 dictámenes de certificación fitosanitaria para la agroexportación, logrando una ejecución del 109\% de la meta programada de 175,593 dictámenes, registrando un desempeño alto. Los productos con mayor certificación son: paltas, uvas, arándanos, cítricos, café, mangos, cebollas, bananas, cacao, quinua y jengibre, que concentran el 84.0\% de la certificación fitosanitaria.
    \item \textbf{Actividad 5003090 “Gestión de Acceso de Nuevos Productos a Mercados Internacionales”} \\
    Durante el 2024, se superó la meta programada de 2 productos con la gestión de apertura de 21 productos a mercados internacionales, que comprenden: palta Hass, fruta fresca a Malasia; arándanos (planta) y palto (planta) a Colombia; arándanos (planta) a Chile; uva de mesa, fruta congelada (mango, palta y arándano), pecanas (c/s cáscara) y castaña (nuez de Brasil) a China; hydrangea (flor cortada), naranja, toronja, limón sutil, limón Tahití y limón (frutos frescos) Eureka a Brasil; mandarina, naranja, toronja y limas ácidas (frutas frescas) a Nueva Zelanda; uva fresca a Ecuador; y mandarina y tangelo (fruto fresco) a Vietnam. Este resultado representa un nivel de ejecución de 1,050.0\% de la meta programada y califica como un desempeño alto.
\end{itemize}
}
\end{justify}

\begin{center}
\textbf{\small TABLA N° 14} \\
\textbf{\small CUMPLIMIENTO DE INDICADORES DE PRODUCCIÓN FÍSICA (PRODUCTO Y ACTIVIDAD), 2024} \\
\end{center}
\vspace{-0.6cm}
\fontsize{9}{9.5}\selectfont
\setlength{\extrarowheight}{2pt} % opcional para darle espacio vertical a las filas

\begin{tabularx}{\textwidth}{
  >{\raggedright\arraybackslash}X
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{2cm}
}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / ACTIVIDAD}} & \textcolor{white}{\textbf{UNIDAD DE MEDIDA}} & \textcolor{white}{\textbf{META FÍSICA ANUAL}} & \textcolor{white}{\textbf{EJECUCIÓN FÍSICA ANUAL}} & \textcolor{white}{\textbf{AVANCE \% (META ANUAL)}} & \textcolor{white}{\textbf{DESEMPEÑO}} \\
\endfirsthead
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{PRODUCTO / ACTIVIDAD}} & \textcolor{white}{\textbf{UNIDAD DE MEDIDA}} & \textcolor{white}{\textbf{META FÍSICA ANUAL}} & \textcolor{white}{\textbf{EJECUCIÓN FÍSICA ANUAL}} & \textcolor{white}{\textbf{AVANCE \% (META ANUAL)}} & \textcolor{white}{\textbf{DESEMPEÑO}} \\
\endhead
\rowcolor[HTML]{EDEDED} 
\raggedright \textbf{3000380.  PRODUCTORES AGRÍCOLAS CON MENOR PRESENCIA DE PLAGAS PRIORIZADAS} & PRODUCTOR & 362,299 & 362,565 & \rowcolor[HTML]{63BE7B} 100.1\% & \rowcolor[HTML]{FFFFFF} Alto \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright 5000189. CONTROL Y/O ERRADICACION DE PLAGAS PRIORIZADAS & HECTAREA & 412,384 & 506,444 & 122.8\% & Alto \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5000200. DIAGNÓSTICO DE PLAGAS DE PRODUCTOS VEGETALES & DIAGNOSTICO & 18,225 & 18,564 & 101.7\% & Alto \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5001308. VIGILANCIA FITOSANITARIA DE PLAGAS PRESENTES & HECTAREA & 2,425,100 & 2,454,379 & 101.2\% & Alto \\
\rowcolor[HTML]{EDEDED}
\raggedright \textbf{3000525. PRODUCTORES AGRÍCOLAS CON CULTIVOS PROTEGIDOS DE LA INTRODUCCIÓN Y DISPERSIÓN DE PLAGAS REGLAMENTADAS} & PRODUCTOR & 2,141,525 & 2,301,739 & \rowcolor[HTML]{63BE7B}107.5\% & \rowcolor[HTML]{FFFFFF} Alto \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5000201. DIAGNOSTICO DE PLAGAS DE PRODUCTOS VEGETALES IMPORTADOS & DIAGNOSTICO & 10,440 & 16,174 & 154.9\% & Alto \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5000297. INSPECCION Y CONTROL DEL INGRESO DE PLANTAS, PRODUCTOS VEGETALES Y OTROS ARTICULOS REGLAMENTADOS & DICTAMEN & 2,002,252 & 3,733,768 & 186.5\% & Alto \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5001309. VIGILANCIA FITOSANITARIA PREVENTIVA DE PLAGAS NO PRESENTES & HECTAREA & 191,538 & 294,255 & 153.6\% & Alto \\
\rowcolor[HTML]{E7E6E6} 
\raggedright \textbf{3000526. PRODUCTORES CON CAPACIDAD DISPONIBLE PARA EL CUMPLIMIENTO DE RESTRICCIONES FITOSANITARIAS DE LOS MERCADOS DE DESTINO} & PRODUCTOR & 21,589 & 18,626 & 86.3\% & Regular \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5000183. CERTIFICACIÓN FITOSANITARIA & DICTAMEN & 175,593 & 191,401 & 109.0\% & Alto \\
\rowcolor[HTML]{FFFFFF} 
\raggedright 5003090. GESTIÓN DE ACCESO DE NUEVOS PRODUCTOS A MERCADOS INTERNACIONALES & PRODUCTO & 2 & 21 & 1050.0\% & Alto \\
\end{tabularx}
\vspace{-15pt}
\begin{flushleft}
\footnotesize \fontsize{9}{11}\selectfont \textbf{Fuente:} Aplicativo CEPLAN V01
\end{flushleft}

\subsection*{\small{b) Ejecución física de los principales proyectos}}


\noindent \fontsize{11}{13}\selectfont \begin{justify} {\textbf{Proyecto 2343984: Erradicación de la Mosca de la Fruta en los Departamentos de Piura, Tumbes, Lambayeque, La Libertad, Cajamarca, Amazonas, Apurímac, Cusco y Puno\\\\}
\fontsize{11}{13}\selectfont
\noindent El proyecto tiene el objetivo de contribuir en el acceso de 875,855 productores hortofrutícolas a servicios fitosanitarios e inició su ejecución en abril de 2019. Al 2024, el monto de inversión del proyecto ascendió a S/ 445,519,329, de los cuales registró un ejecución acumulada de S/ 429,821,705 que representa un avance financiero acumulado de 96.5\%. \\

\noindent Por su parte, PRODESA ejecutó 2 proyectos de inversión que concentraron el 97.9\% del PIM registrando un avance promedio de 96.7\%. Estas inversiones estuvieron vinculadas a la gestión de la unidad ejecutora y la erradicación de la mosca de la fruta en los departamentos de Piura, Tumbes, Lambayeque, La Libertad, Cajamarca, Amazonas, Apurímac, Cusco y Puno. \\\\\\

\noindent \textbf{\underline{Principales resultados del 2024}}

\begin{itemize}
    \item Protección sanitaria vegetal a través de la provisión de 997,834 servicios de revisión de trampas, donde más del 75.0\% se concentraron en las regiones de Piura (39.7\%), Lambayeque (26.3\%) y Cajamarca (11.6\%).
    \item Se logró atender a 142,350 ha con acciones de control de plagas en la etapa de supresión, erradicación y post erradicación, a través de la implementación de acciones operativas de protección sanitaria vegetal.
\end{itemize}
}
\end{justify}
\subsection{Análisis del cumplimiento de metas de indicadores de desempeño}

\subsection*{\small{a) Indicadores de desempeño de resultado específico}}
\\
\noindent \fontsize{11}{13}\selectfont \begin{justify} { En el periodo 2024, los indicadores de desempeño del PP 0040 muestran un avance significativo en el cumplimiento de sus metas. La reducción de las pérdidas anuales por la presencia de plagas en el pais alcanzó el 15.6\% que representan un cumplimiento del 102.6\% de la meta establecida (15.2\%), obteniendo un desempeño alto. La presencia de plagas en los cultivos resultó en pérdidas de S/ 5.9 mil millones a precios reales, afectando considerablemente la productividad y la rentabilidad del sector agrícola.\\

\noindent Mientras que, el índice de acceso fitosanitario a mercados internacionales alcanzó un 10.5\% que representa un 110.5\% de lo programado (9.5\%), obteniendo un desempeño alto. Hasta diciembre del año 2024 , existen 251 mercados abiertos (producto-país). Los países con mayores productos son: Brasil (39 productos), Chile (22 productos), Argentina (21 productos) y China (16 productos). Entre los productos con más mercados se ubica: palta en 25 países y uva en 23, semillas en 21, arándano en 15 y limón en 15. Este indicador refleja el esfuerzo del Perú por asegurar que todos los productos exportables cuenten con acceso fitosanitario a sus mercados de destino, lo que es fundamental para garantizar la calidad y seguridad sanitaria de las exportaciones.\\

\noindent Por otro lado, en el indicador reducción de tasa de rechazos en planta empacadora se logró una ejecución del 0.81\% que representa un nivel de cumplimiento del 135.0\% de la meta programada (0.6\%), obteniendo un desempeño alto. Los productos con mayor certificación fitosanitaria incluyen: paltas, uvas, arándanos, cítricos, café, mangos, cebollas, bananas, cacao, quinua y jengibre, los cuales concentran el 84\% de la certificación fitosanitaria total. Los rechazos, en su mayoría, se producen en productos como paltas, uvas, cítricos y espárragos. A pesar de los esfuerzos por incrementar la oferta de plantas y productos vegetales sanos en el mercado de destino, el avance alcanzado en 2024 aún se encuentra por debajo de las expectativas, lo que señala la necesidad de reforzar los procedimientos fitosanitarios y las inspecciones en las plantas empacadoras certificadas, especialmente para los productos de mayor riesgo fitosanitario.
}
\end{justify}

\begin{center}
\textbf{\small Tabla N° 15} \\
\textbf{\small INDICADORES DE DESEMPEÑO DE RESULTADO ESPECÍFICO DEL PP 0040, 2024} \\
 % Título encima del gráfico en el formato solicitado
\end{center}
\vspace{60pt}

\begin{table}[ht]
\centering
\resizebox{\textwidth}{!}{%
\fontsize{9}{9.5}\selectfont \begin{tabular}{m{6.0cm} c c c c c}
\rowcolor[HTML]{538135} 
\textcolor{white}{\textbf{INDICADOR DE DESEMPEÑO DE RESULTADO ESPECÍFICO}} & \textcolor{white}{\textbf{META 2024}} & \textcolor{white}{\textbf{EJECUCIÓN 2024}} & \textcolor{white}{\textbf{AVANCE \%}} \\ 
\raggedright \rowcolor[HTML]{E2EFD9} Reducción de las pérdidas anuales por la presencia de plagas en el pais & \rowcolor[HTML]{FFFFFF} 15.2 & \rowcolor[HTML]{FFFFFF} 15.6 & \rowcolor[HTML]{63BE7B} 102.6\% \\ 
\rowcolor[HTML]{FFFFFF} 
\raggedright \rowcolor[HTML]{E2EFD9} Índice de acceso fitosanitario a mercados internacionales & \rowcolor[HTML]{FFFFFF}9.5 & \rowcolor[HTML]{FFFFFF}10.5 & \rowcolor[HTML]{63BE7B} 110.5\% \\ 
\rowcolor[HTML]{FFFFFF}
\raggedright \rowcolor[HTML]{E2EFD9} Reducción de tasa de rechazos en planta empacadora & \rowcolor[HTML]{FFFFFF}0.6 & \rowcolor[HTML]{FFFFFF}0.81 & \rowcolor[HTML]{63BE7B} 135.0\% \\ 
\end{tabular}%
}
\vspace{-10pt}
\begin{flushleft}
\footnotesize \fontsize{9}{11}\selectfont \textbf{Fuente:} \text{Aplicativo SICAL-MEF}
\end{flushleft}
\end{table}
\vspace{-1cm}
\subsection*{\small{b) Indicadores de desempeño de producto}}
\\
\noindent \fontsize{11}{13}\selectfont \begin{justify} { La Tabla N°16 se presenta los resultados de los indicadores de desempeño de producto del PP 0040 para el año 2024.
\\

\noindent \textbf{\underline{Producto 3000380: Productores agrícolas con menor presencia de plagas priorizadas}}\\

\noindent Este producto cuenta con dos indicadores:\\

\noindent El indicador “Superficie libre de plagas declarada” evalúa las áreas declaradas por el SENASA como libres de plagas, las cuales requieren acciones preventivas y permanentes como vigilancia, trampeo, muestreo y control focalizado, incluyendo la liberación de moscas estériles. En 2024, la superficie libre de plagas alcanzó un 10.0\%, alcanzando un nivel de cumplimiento de 125.0\% de la meta programada (8.0\%), obteniendo un desempeño alto. La superficie libre de plagas se concentra en el área hortofrutícola de los departamentos de Tacna y Moquegua con cultivo hospedante de la plaga de la mosca de la fruta. \\

\noindent Mientras que,  el indicador "Reducción de la tasa de incidencia de plagas priorizadas" evalúa el impacto del Manejo Integrado de Plagas (MIP) en comparación con el manejo fitosanitario tradicional, midiendo la incidencia inicial y final de la plaga clave en los predios de los agricultores que adoptaron esta metodología. En 2024, la tasa de incidencia de plagas se redujo en un 14.0\%, superando significativamente con un nivel de cumplimiento del 150.5\% de la meta programada (9.3\%), registrando un desempeño alto. Este resultado destaca la efectividad del MIP en la reducción de plagas.\\

\noindent \textbf{\underline{Producto 3000525 Productores agrícolas con cultivos protegidos de la introducción}}\\ \textbf{\underline{y dispersión de plagas reglamentadas}}\\

\noindent Este producto cuenta con un indicador: “Plaga reglamentada introducida”. Este indicador es clave para prevenir la propagación de plagas que podrían causar graves pérdidas al sector agroexportador, por lo que el proceso de cuarentena post-entrada asegura un monitoreo exhaustivo para detectar cualquier signo de infestación, tomando medidas inmediatas en caso de diagnóstico positivo. \\

\noindent En el 2024, la plaga reglamentada introducida fue “Xylella fastidiosa”, que principalmente ataca al cultivo del café, detectada en Junín. A pesar de que no se logró la meta establecida de 0 plagas reglamentadas introducidas, es importante destacar que, se desarrolló un plan de contención para evitar su diseminación (inmovlización de productos de la zona infestada, capacitación y control de la plaga).\\

\noindent \textbf{\underline{Producto 3000526 Productores con capacidad disponible para el cumplimiento de}}\\ \textbf{\underline{restricciones fitosanitarias de los mercados de destino}}\\

\noindent Este producto cuenta con un indicador: “Porcentaje de productores agrícolas con acceso a mercado”. Este indicador es crucial para evaluar la capacidad de los productores agrícolas para acceder a mercados internacionales, lo que implica superar las barreras fitosanitarias y ampliar su oferta de productos. Para 2024, se programó un 4.2\%; sin embargo, no se dispone de información sobre la ejecución debido a que los resultados de la Encuesta Nacional Agropecuaria (ENA) 2024 se encuentran aún en proceso.\\
}
\end{justify}
\begin{center}
\textbf{\small Tabla N° 16} \\
\textbf{\small INDICADORES DE DESEMPEÑO DE PRODUCTO DEL PP 0040, 2024} \\
 % Título encima del gráfico en el formato solicitado
\end{center}
\vspace{-15pt}
\renewcommand{\arraystretch}{1.3} % espacio vertical en filas
\setlength{\tabcolsep}{9pt} % espacio horizontal en celdas

{\fontsize{9}{11}\selectfont
\begin{tabularx}
{\textwidth}{
  >{\raggedright\arraybackslash}X
  >{\raggedright\arraybackslash}X
  >{\centering\arraybackslash}m{1.8cm}
  >{\centering\arraybackslash}m{2cm}
  >{\centering\arraybackslash}m{1.8cm}
}
\rowcolor[HTML]{538135}
\textcolor{white}{\textbf{PRODUCTO PRESUPUESTAL}} & 
\textcolor{white}{\textbf{INDICADOR DE DESEMPEÑO DE PRODUCTO}} & 
\textcolor{white}{\textbf{META}} & 
\textcolor{white}{\textbf{EJECUCIÓN}} &  
\textcolor{white}{\textbf{AVANCE \%}} \\
\rowcolor[HTML]{E2EFD9}
{\cellcolor[HTML]{E2EFD9}3000380 Productores agrícolas con menor presencia de plagas priorizadas} &
\rowcolor[HTML]{E2EFD9} Superficie libre de plagas declarada & \rowcolor[HTML]{FFFFFF} 8.0 &
\rowcolor[HTML]{FFFFFF} 10.0 &
\rowcolor[HTML]{63BE7B} 125.0 \% \\
\rowcolor[HTML]{E2EFD9} & Reducción de la tasa de incidencia de plagas priorizadas & \rowcolor[HTML]{FFFFFF} 9.3 & \rowcolor[HTML]{FFFFFF} 14.0 & \rowcolor[HTML]{63BE7B} 150.5 \% \\
\rowcolor[HTML]{E2EFD9}
\raggedright 3000525 Productores agrícolas con cultivos protegidos de la introducción y dispersión de plagas reglamentadas & \rowcolor[HTML]{E2EFD9} Plaga reglamentada introducida & \rowcolor[HTML]{FFFFFF} 0 & \rowcolor[HTML]{FFFFFF} 1 & \rowcolor[HTML]{F8696B} 0.0 \% \\
\rowcolor[HTML]{E2EFD9}
\raggedright 3000526 Productores con capacidad disponible para el cumplimiento de restricciones fitosanitarias de los mercados de destino & \rowcolor[HTML]{E2EFD9} Porcentaje de productores agrícolas con acceso a mercado & \rowcolor[HTML]{FFFFFF} 4.2 & \rowcolor[HTML]{FFFFFF} - & \rowcolor[HTML]{F8696B} - \\
\end{tabularx}
}
\vspace{-0.7cm}
\begin{flushleft}
\footnotesize \fontsize{9}{11}\selectfont \textbf{Fuente:} \text{Aplicativo SICAL-MEF}
\end{flushleft}

\section{Factores que incidieron en el desempeño del programa}

\begin{itemize}
    \item El personal del programa demostró un alto compromiso con el logro de los objetivos institucionales en sanidad animal, siendo su dedicación clave para la ejecución efectiva de las actividades programadas a nivel nacional y contribuyendo directamente a los avances en los indicadores de producción física (actividades y productos).
    \item La colaboración activa de los agricultores y las entidades locales, manifestada en la notificación temprana de la aparición de plagas, constituyó un factor clave y positivo. Esta comunicación oportuna permitió una respuesta más rápida y eficiente de las autoridades fitosanitarias. Como resultado directo, las actividades de vigilancia se intensificaron y dirigieron de manera efectiva, superando la meta programada de hectáreas vigiladas.
    \item El seguimiento continuo de las actividades programadas, a cargo de personal debidamente capacitado para la tarea, permitió identificar rápidamente cualquier desviación, ajustar las acciones operativas y asegurar la correcta ejecución de las tareas, contribuyendo significativamente al cumplimiento de las metas físicas establecidas para el periodo.
    \item La asignación oportuna de recursos para la ejecución de las inversiones y el seguimiento continuo a las órdenes de compra permitió al PRODESA alcanzar los objetivos propuestos para el PP 0040.
\end{itemize}

\section{Medidas para mejorar el desempeño del programa}

\begin{itemize}
    \item Fortalecer el sistema de asistencia técnica y seguimiento en campo para los agricultores que implementan el MIP. Esto implica no solo la capacitación inicial, sino un acompañamiento regular y personalizado por parte de técnicos especializados que verifiquen la correcta aplicación de las prácticas del MIP (monitoreo, umbrales, uso adecuado de métodos de control), resuelvan dudas específicas y adapten las estrategias a las condiciones locales. Este seguimiento asegura una implementación más efectiva del MIP, optimizando el control de plagas y la calidad fitosanitaria de la producción.
    \item Fomentar campañas de comunicacionales para sensibilizar la importancia de la notificación oportuna para permitir una respuesta rápida y efectiva en el control y erradicación.
    \item Implementar y optimizar plataformas tecnológicas para la recolección, consolidación y análisis en tiempo real de datos sobre la incidencia de plagas, la ejecución de actividades de control, y los resultados de las inspecciones (incluyendo causas de rechazo). Contar con datos precisos y oportunos es fundamental para realizar análisis de desempeño más profundos, identificar áreas problemáticas rápidamente y ajustar las estrategias de intervención de manera informada.
\end{itemize}

\section{Conclusiones}

\begin{itemize}
    \item Ejecución Presupuestal Eficiente: El Programa Presupuestal 0040 demostró una alta eficiencia en la ejecución de su presupuesto durante el año 2024, alcanzando un nivel de ejecución global del 97.0\%. Esto refleja una gestión financiera sólida y un uso eficaz de los recursos asignados para las actividades del programa.
    \item Cumplimiento de Metas Financieras: La mayoría de los niveles de gobierno (nacional y regional) y las genéricas de gasto mostraron un desempeño "Alto" en la ejecución presupuestal, superando el 95\%. Sin embargo, se identificaron áreas de mejora en la ejecución por parte del gobierno local y en la fuente de financiamiento de Donaciones y Transferencias, que mostraron un desempeño "Regular" y "Bajo" respectivamente.
    \item Cumplimiento de Metas Financieras: La mayoría de los niveles de gobierno (nacional y regional) y las genéricas de gasto mostraron un desempeño "Alto" en la ejecución presupuestal, superando el 95\%. Sin embargo, se identificaron áreas de mejora en la ejecución por parte del gobierno local y en la fuente de financiamiento de Donaciones y Transferencias, que mostraron un desempeño "Regular" y "Bajo" respectivamente.
    \item Impacto en la Sanidad Vegetal: Las acciones del programa contribuyeron a mantener y mejorar la sanidad vegetal en el país, lo cual se evidencia en la protección de cultivos contra plagas, la gestión de acceso a mercados internacionales y el control de plagas priorizadas. La apertura de nuevos mercados internacionales para productos agrícolas peruanos es un claro indicador del éxito del programa en facilitar el comercio y cumplir con las exigencias fitosanitarias de los países de destino.
    \item Desempeño Variable de Indicadores: Se presentó un alto desempeño en la ejecución presupuestal, así como en el desempeño de los indicadores de desempeño y de producción física.
    \item Necesidad de Mejoras Continuas: A pesar de los éxitos, el informe identifica la necesidad de continuar mejorando la eficiencia en ciertas áreas, como la ejecución presupuestal a nivel local y en el establecimiento de metas de los indicadores. Se requiere un enfoque continuo en la optimización de los procesos y la adaptación a los desafíos emergentes en el ámbito de la sanidad vegetal.
\end{itemize}

\section{Recomendaciones}

\begin{itemize}
    \item Para optimizar la programación futura, se recomienda implementar un análisis de tendencias de ejecución en las actividades y productos del programa. Esto implica revisar la tendencia de los logros alcanzados, ajustar metas en función de la demanda real proyectada, y analizar los factores que impulsaron las variaciones para anticipar futuras dinámicas del sector agrícola.
    \item Fomentar activamente la generación y consolidación de alianzas estratégicas, tanto a nivel interinstitucional dentro del gobierno como con actores clave del sector privado, con el fin primordial de asegurar y elevar continuamente el estatus sanitario de los productos agrícolas peruanos destinados a la exportación. Esto se logrará a través de la concertación y aplicación efectiva de políticas públicas coordinadas, facilitando el cumplimiento de los requisitos sanitarios de los mercados internacionales y promoviendo la competitividad del sector agroexportador en el ámbito global.
    \item Fomentar una comunicación interna y externa más fluida y estructurada entre todos los actores que intervienen en la ejecución del programa. Una mejor coordinación y un intercambio de información proactivo pueden ayudar a anticipar y resolver cuellos de botella, asegurar la alineación de actividades y recursos, y mejorar la capacidad de respuesta ante imprevistos durante la implementación de los proyectos.
\end{itemize}

\end{document}

