java c
ELEN 4810 Final Exam
1. Z-transform. A   discrete-time   LTI   system   has   transfer   function

Please   answer   the   following   questions:
Part 1. Please   plot   the   pole-zero   diagram   of   H(z),   labeling   all   poles   and   zeros.    You   can   use   the axes   on   the   next   page.
Part 2. Which   of the   following   best   describes   this   system?
HIGH   PASS            LOW   PASS               ALL   PASS            BAND   PASS
Please   justify   your   answer. 
Part 3. Could   the   system   be   stable   and   causal?   Why   or   why   not?
Part 4. Could   the   impulse   response   h[n]   be   real   valued?   Why   or   why   not?Part    5. Please   determine   the   transfer   function   H′ (z) of   a   system   which   is causal and stable,   and ensures   for   the   following   system   which   applies   H   and   H′ in   series, the   output   y[n] satisfies |Y   (ejω )|   =   |X(ejω )| for every input x[n] : 
2.    Generalized Linear Phase Systems. Consider   an   FIR   generalized   linear   phase   system, with   real   valued   impulse   response   h[n],   transfer   function   H(z)   and   zeros   ζ1,...,ζL−1   . 
Please answer the following questions: 
Part (i). What   are the poles of H(z)?    For   any repeated poles,   please   indicate   their   multiplicity.    If   it   is   not   possible   to   determine   the   poles   from   the   given   information,   please   explain   why.
Part (ii). Set   h′ [n] =   (−1)n+1h[n].   Does   the   resulting   system   have   generalized   linear   phase?   Why or   why   not?
Part (iii). Please give   an expression for the   zeros ζ1(′),...,ζL(′)−1 of   H′ (z)   in   terms   of ζ1,...,ζL−1   .
Part (iv). Suppose   we   wish   for   h′ [n] to   be   a low pass system.   What   types   of   canonical   generalized linear   phase   system/systems   should   we   not   choose   for   h[n]?   Why?
3.    Spectrograms. A   continuous-time   chirp   signal
xc   (t) =   cos(αt2   )
is   sampled   with   a   sampling   period
Ts    =   0.03secondsto   produce   a   discrete   time   signal   x[n].      We   compute   the   Short-Time   Fourier   Transform   (STFT),   X[r,   k],   using   a   time   stride   of   R   =   10   samples,   N   =   512   frequency   samples,   and   a   window   w[n]   of   length   L.         We   plot   the   magnitude   of   the   Short-Time   Fourier   Transform      (STFT)    |X[r,   k]|,   for   r   =   代 写ELEN 4810 Final ExamSQL
代做程序编程语言0, . . . , 2400   and   k   =   0, . . . , 255:
Above,   the   graph   at   right   plots   the   vertical   slice
X[1000,   0],   X[1000, 1],...,   X[1000,   255].
(Note,   that   N   = 512;   here   we   only   show   X|[r,   k]|    for   k   < N/2). 
Please answer the following questions: 
Part (a). Please   estimate   the   chirp   parameter   α   .   Justify   your   answer!
Part (b). Why   does   the   spectrogram   exhibit   a   rising   line   and   a   falling   line?
Part (c). Which   of the   following   windows   was   used   to   determine   the   spectrogram?
RECTANGULAR                         HAMMING 
Please   explain   your   answer!
Part (d). Please   estimate   the   length   L   of the   window,   based   on   the   available   information.   Note: your estimate does not need   to    be   perfect, but   please explain how you arrived at it.
4.       IIR    Filter    Design    and    Bilinear    Transform. We    generate    a   discrete   time   IIR   filter   by   applying   bilinear   transformation
to   a   continuous   time   system, with   transfer   function   Hc   (s).    Here   is   the   magnitude   response   |H(ejω )|   :
Please answer the following questions: 
Part A. Which   of the   following   best   describes   this   filter?
BUTTERWORTH          CHEBYSCHEV I             CHEBYSCHEV II          ELLIPTIC
Part B. Our   continuous   time   filter   Hc   (s)   has   poles   at 

and a zero of multiplicity three   at   s   =   ∞   . What are the poles and zeros of the discrete time system H(z)? 
Part C. What   is   one   advantage   of FIR   filters   (e.g.,   designed   by   windowing   or   optimization)   com-   pared   to   the   IIR   design   in   part   A?
Part D. Suppose   we   generate   a   new   system,   by   setting   H′ (z)   =   H(z)H*   (1/z*   ). What is the phase response ∠H′ (ejω ) of the new system? Part E. The   system   H′ has   order   six      (six   poles   and   six   zeros).    Based   on   your   answer   to   Part   D,   please   describe   one   advantage   to   the   system   H′ ,   compared   directly   designing   an   order   six   system   using   bilinear   transformation.
Part F. Can   the   system   H′ (z)   be   both stable and causal?   Why   or   why   not?
Part G. Please   give   an   expression   for   the   impulse   response   h′ [n]   in   terms   of the   impulse   response   h[n].



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
