# Johnson K C

**Machine learning research engineer.** Computer Science, Morgan State University, Class of 2027. Baltimore, Maryland.

Email: [johnsonkc201@gmail.com](mailto:johnsonkc201@gmail.com)
LinkedIn: [linkedin.com/in/johnsonkc](https://www.linkedin.com/in/johnsonkc)

**Currently seeking:** Fall 2027 internships in machine learning research and ML engineering.

## About

I am training to be a machine learning research engineer: the person who takes a method out of a paper, implements it correctly, proves it matches the reference, and turns it into code the rest of the lab can build on.

That one goal shapes everything below. My research is in optimal transport and geometric machine learning. My open-source work goes upstream into the scientific Python stack those methods run on. My projects are where I practice getting a model out of a notebook and into something people actually run.

I graduate in Spring 2027 with a 4.0 GPA.

## Research

**Machine Learning Researcher**, Morgan State University, NIH NIDA R21
Advised by Dr. Pilhwa Lee. Extending optimal transport gradient flows onto symmetric positive definite matrices, applied to brain connectivity. I implemented a published sliced Wasserstein flow on the SPD manifold, validated it against our own log-domain formulation, and built the test suite that keeps both implementations honest.

**Machine Learning Researcher**, UC San Diego HDSI, STARS 2026
Advised by Dr. Duncan Watson-Parris, in the climate modeling group. Online bias correction for JAX-based general circulation model physics.

**NLP Research Intern**, Luminoso Technologies
Enterprise natural language processing and text analytics tooling.

**Break Through Tech AI Fellow**, Cornell Tech, Machine Learning Foundations track, 2026/27 cohort.

## Open source

I use these libraries in my research, so I fix them upstream when they break. Merged:

| Project | Contribution |
| --- | --- |
| [equinox](https://github.com/patrick-kidger/equinox/pull/1253) | Treat JAX and NumPy arrays as interchangeable when deserialising |
| [scanpy](https://github.com/scverse/scanpy/pull/4256) | Use the non-zero median as `target_sum` on the sparse normalization path |
| [xarray](https://github.com/pydata/xarray/pull/11477) | Fix stacking of dimensions with falsy names |
| [sqlite-utils](https://github.com/simonw/sqlite-utils/pull/751) | Honor `--no-headers` for formatted and table output |
| [ai-job-search](https://github.com/MadsLorentzen/ai-job-search/pull/230) | Store standalone count columns as counts rather than indexes |

Under review:

| Project | Contribution |
| --- | --- |
| [transformers](https://github.com/huggingface/transformers/pull/46942) | Fix dtype cast in TimesFM 2.5 `ResidualBlock` for quantized weights |
| [PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric/pull/10758) | Fix the `dense_to_sparse` backward pass for three-dimensional input |
| [zarr](https://github.com/zarr-developers/zarr-python/pull/4189) | Allow `require_array` to accept a `ZDType` |
| [anndata](https://github.com/scverse/anndata/pull/2571) | Suggest the correct store class when reading a packed zarr store by path |

## Selected projects

**[Echo Flow](https://github.com/JOhnsonKC201/Echo_FLOW)**
Local-first voice dictation for Windows. Whisper transcribes on device and a local language model cleans the text, so audio never leaves the machine. It learns your vocabulary and casing from your own corrections, supports 16 languages, and ships with a 1,450-test suite. Python, Whisper, Ollama.

**[pixelpets](https://github.com/JOhnsonKC201/pixelpets)**
A pixel cat or dog that lives on your desktop, watches your cursor, and reacts when you type. 14 cat coats and 14 dog breeds, all original art and procedural audio. [Try it in the browser](https://pixelcat-jet.vercel.app), no install required. JavaScript, Electron.

**[Yahtri](https://yahtri.com)**
Hyperlocal resale marketplace. Listings are generated from a photo by a vision model, with map-first browsing and price-drop alerts. React, FastAPI, Supabase.

**BearBoard**
Student collaboration platform for Morgan State, with an LLM-backed quiz generator. I led the work that took it multi-worker on a shared Redis backplane and closed a set of critical authentication and rate-limiting issues found in review. React, FastAPI, Postgres.

**[Diabetes prediction from sparse EHR data](https://github.com/JOhnsonKC201/Diabetes_Prediction_Logistic_Regression)**
Logistic regression for early Type 2 diabetes detection in low-resource settings. Dataset, model, and write-up.

## Tools

**Machine learning:** PyTorch, JAX, Equinox, scikit-learn, Hugging Face Transformers, NumPy, pandas, Scanpy, AnnData, Whisper
**Languages:** Python, R, SQL, TypeScript, JavaScript, Bash
**Systems:** FastAPI, React, Postgres, Redis, Docker, Git, Linux

## Beyond the lab
APEx Honors at NSBE. Tau Sigma and NSLS honor societies. SABCYL Cohort 4 through the Center for Urban Families. Peer mentor for transfer students at Morgan State.

## Contact
<svg xmlns="http://www.w3.org/2000/svg" width="1317" height="728" viewBox="0 0 1317 728" role="img" aria-label="ASCII GitHub profile card for JOhnsonKC201">
  <rect x="0.5" y="0.5" width="1316" height="727" rx="8" fill="#0d1117" stroke="#30363d"/>
  <text x="28" y="34.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">xj:            |xooooooooooooooooooxoxxj  :: : : :       :      : : : : :      ::        :                         ::'::::: :             '?</text>
  <text x="28" y="44.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">j::::::::: :   :jxxxxxxxxxjvjjvv======!:</text>
  <text x="28" y="53.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">j::::::::::::: : :: :</text>
  <text x="28" y="63.400000000000006" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">j::                                                            :        :</text>
  <text x="28" y="73" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">j::                                                        :::::    :::   :::::::.:_..._:                           :  :</text>
  <text x="28" y="82.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">:::                                                                          : ::: ::::jj:::::::::j:jjjjjjjjjjjjjjj::j::j:::</text>
  <text x="28" y="92.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">::: :.__________________.:::::::                                                      :::: :: :::jjjjjjjjjjjjjjjjjjjjjjjjj:::</text>
  <text x="28" y="101.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">::::juoo@oooooooooooooooxjjjjjjjjjjjjjjjjjj::                                          :::::::::::::jjxxjjjjjjjjjjjjjjjjj::::::::</text>
  <text x="28" y="111.39999999999999" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">:::jjoo@@@ooooooooooo@oooxxxjjjxxxxxxxxxxxxu;_____::.: :                                     :::::::jjjxxxxxxxxjjjjjjjjjjj::::::::</text>
  <text x="28" y="121" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">:::jxxoooxooxxxxxxxxoooooxxjjxxxxxxxxxxxooooooooxxc:!!::                     :                    :jjjxoooooooxxjjjjjjjjjjj:::::::</text>
  <text x="28" y="130.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">:::jxxoxxxxxxxxxjjjxoo@ooxxxxxxxxxxxxxxxooooooxxxxxj:             ::::jjjj:jjjjj_.:              :::jiooooooooxxjjjjjjjjjjj:::::::::</text>
  <text x="28" y="140.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">:::jxxoxxjjjjxxxjjjxoooooxxxxxxxxxoxxxxxooo@ooxxxjjj:          ::::jjjxxxxxxxxxxxxxu;__.:      ::::::jxoooooooxjjjjjjjjjjjj::::::::::::::</text>
  <text x="28" y="149.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxxoxxjjxxxxxxxxxoo@ooxxxxxxxxxxxxxxxooooooxxxjj:        :::::jjjxxxxxxxxxoooooooooxxuu;.:    :::::xxvjjjjjj::::::::::::::::::::::::::</text>
  <text x="28" y="159.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxooooooooooooooooooooxxxxxjjxxxxxxxxooo@ooxxxx|        ::::::jjjxxooooooooooooooooo@oooou/      :jjj::: :::::::::::::::: ::::::::::::</text>
  <text x="28" y="169" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxxoooo@oooooooooo@oooxxxjjjjxxxxxxxxoooooooxxx|        :::::jjjjxxooooooooooooo@o@@@@@@ooo/.   ::::j::::::::::::::::::::::::::::::: :</text>
  <text x="28" y="178.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxxoo@ooo@ooooooooooooxxxxxxxxxxxxxxxooo@oooxxx:::      ::::jjjjxxxooooooooooo@oo@o@o@o@@@@o/. ::::::j::::::::j::j:jjjxxj::::::::j::::::</text>
  <text x="28" y="188.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxooooo@ooooo@ooooo@ooooooooooooooooooooooooxxx;j     :::::jjjjxxxooooooooooooo@o@@@@@@@o@@oo|:: : :jjjjjjjjjjjjjjj:jjxxj:::::::jjjjjj::</text>
  <text x="28" y="197.79999999999998" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxoooooooooooooooooooooooooooooooooooooo@ooooooo|    :::::::!!!!=1xoooooooooooo@o@o@@@@@@@o@xj:    ::::jjjjjjjjjjj:::::::::::::::jj:::::</text>
  <text x="28" y="207.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxoooo@oooooooooooo@oooxxxxxxxoooooooooooooooooo|   ::::  ::...::::jxxooooooooooow$$$o@@@o@oo|:  ::: :::::::::::::::: : :::::::: : :</text>
  <text x="28" y="217" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> ::jxxooooooooooooooooooxxjjjjjjjjxxxxxxxxxooooooox   ::::::::jjxxxxjjjjjxxxooooxxjjj::jjxxooo@o|:::::      : : : :</text>
  <text x="28" y="226.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> : ::!!====!=!!!!!!!!!!!': :    :::::::: ::::::::::   ::::::::::-^voxjjj:jjxooooxxxjjxxxooooooo@o|::</text>
  <text x="28" y="236.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  :                                                  ::::::: :::: :axjjj::io@@ooojj::!!o$ooo@o@@o|::</text>
  <text x="28" y="245.79999999999998" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">                              ::__j:            :::  :j:j:::::jjjjxxxxj::jxo@@@ooujjj:::ijnoo@@@o|::</text>
  <text x="28" y="255.39999999999998" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  :                         ::jjxxox|      ::jjj:::: :::jjjjxxxxxxxxxxj::jxo@@@@ooxxjxxxooogo@@@o::                    ::::::::::::::::::::</text>
  <text x="28" y="265" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  :::::jjjjjj::             ::jjxoooj::   ::xxxx:::: :::jjjxxxoooooxxj::jjxo@@o@@@oooooo@@@@@@@@oj_g/                ::jxxxxxxxxxxjjjjjjjj::</text>
  <text x="28" y="274.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jjxxxxxxxjj:     :.....::::jxoooxj::   jjxoo;::  ::::jjxxooooooxj::jjxoo@@@@@@@o@o@@@@@@@@@@|uoxx::::::          :jxxoxxxxxxxxxxxxxjjj::</text>
  <text x="28" y="284.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jxoooooxxj:::  ::jxxxxxxj::jxoooxj::   :jxxo|:   ::::jjjxxooooxj:jj!:xxoooo@o@ooo@o@@@@@@@@@xg@xxjjjjjj::::::j::::jxxoooxxxxxxoooxxjjj::</text>
  <text x="28" y="293.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::xxoooooxxj:::::jjxoooooxjj:jxoooxjj::  :jxxo|:::::::::jjxxxoxxjj::::::jxogjxooooooo@@@@@@@@oxoooxxjjjxxjjjjjjjjjjjjxxooooxxxxxooooxjjj::</text>
  <text x="28" y="303.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jxoooooxxjjjj:jjxxoooooxxj:jxooooxxjjj::jjxoxj:::::::::jjjxxjj:::::jjxxxooo@@@ooooooo@o@o@oooxopxxjjjxxxjjjjjjjjjjjxxoooooxxxxooooxjjjj:</text>
  <text x="28" y="313" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jxoooooxxjjjjj:jjxoooooxxjjjxooooxxxjjjjjjxxoxujj;::::::jjjj::::jjjj1xooo@@o@@oooooooooo@o@@@ooxxxj::jxxxxxjjjjjjjjxxoooooxxxxxoxxxjjj::</text>
  <text x="28" y="322.59999999999997" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jxxooooxxjjjjj:jjxoooooxxjjxxooooxxxxjj:jjxoooxoox::::::jjjxj:::::jjjjxxxooooooxxo@ooooo@o@@@owxxxjj:jxxxxxjjjjjjjjxxoooxxxxxxxxxxjjjj::</text>
  <text x="28" y="332.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  :::jxxoooxxjjjjj::jxoooooxxjjxxooooxxxxjj:jjxxxxxxxxj:::::jjjxjj::::jxxoxooooooxjjjoo@o@o@opxowxxxxxjj::jxxjjjjjjjjjjxxooxxxxxxxxxxxjjjj::</text>
  <text x="28" y="341.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   ::jxxoooxxjjjjj:jjxoooooxxxxooo@ooxxxjjjjjjxooooooou::::::jjjjjjjjjjjxxxooooo@ooooooo@oo@oxxxxxxxxxjj :jxxxjjjjjjjjjxxoooxxxoxxxxxxxjjjj:</text>
  <text x="28" y="351.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  :::jxxxxxxxjjjjj:jjxooooooxoooo@o@oxxxxjjjxoooooooooo/:::j::j::jjjjjjxxxxxooo@o@ooooooo@oooxxxxxxxxxjj: :xxxjjj:jjjjjxxxoooxoooxxxxxxjjjj:</text>
  <text x="28" y="361" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jxxoooooxxjj:::jjxooooooxxxxxooooxxxjjjjxooooo@ooooo|::::::::::jjjxxoooo@o@o@ooooooooooIjxxxoooooxxj: :jxxj:::::::jjxxooooxoxxxxxxxjjjj:</text>
  <text x="28" y="370.59999999999997" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::xoooooooox:::::jjxooooooxxjjxxoooxxxjjjjxooooooooooo|:::j:::j::jjjxxooo@@@@@@@@o@ooooojjjxxooooooxxj:  jxxjj:::::::jxxoooxxxxxxxxxxjjj::</text>
  <text x="28" y="380.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::jxooooooxxjjjjjjjxoooooxxjjjxxoooxjjjjjjjxoooooxxxxxj:::::j:j:j:jjjxoooooooo@oooooooo|::jjjjjjjxjjj:: ::jj::::::::::jjjjjjjjjjjjj::::::</text>
  <text x="28" y="389.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  :::jjjjjjjj:::::::::!!!!!!:::jjj1xxv:::::::jjjjjj:j!!j:::::::::jjjjjjjxxxxooooooooooo@o|: ::::::::::: :  : :: : : :  : : : :</text>
  <text x="28" y="399.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   :: : : :::        :             :                 :::::::::::::::j:jjjjjjxxxxxooooo@o@@/:</text>
  <text x="28" y="409" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">                                                    _j: ::j:j:j::::jjjjjjxxxooooooo@o@o@oq@//</text>
  <text x="28" y="418.59999999999997" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   :                                              _jjj| ::jjjjjj:jjjjjxxooooo@@@@@o@o@@ooq@@g/:                    :</text>
  <text x="28" y="428.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  : : ::jjjjjjjjjjjjjjjjjjjjjjjjjjjj::         ._jjjxx| ::jjjjjjj:jjjjjxooo@o@o@o@oo@o@@|q@@@@g_-_::        : : :   : : : :</text>
  <text x="28" y="437.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::jxxxxxoxoooooxoooxoxooxoxoxxxxj:  _-_uxxjjjjjjxo| ::jjjjjjjjjjjjjxxooo@o@o@o@o@@oolo@@@@@@@@@g//.: :    :  :         :</text>
  <text x="28" y="447.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::jxooooooooooooooooooooooooooooxuxxxxoxxjjjjjjxxoo :jjjjjjjjjjjjxxxooo@o@@o@o@oo@o]|@@@@@@@@@ooo@@@gg---.: : ::::::::</text>
  <text x="28" y="457" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::jxoooooooooxxxj=jjjxxxooooooxooooxxxooxxxxjjjxooo::jjjjjjxxjjjjxxoooo@oo@ooooooo\:|@@@@@@@@@@gxo@@@@@@@@gg-_j::jjj::::::::::::::: : :</text>
  <text x="28" y="466.59999999999997" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::jxooooooxxjjj:::::__ugooooxxoooooxxoowxxxxxjjxo@o|:jjjjjjjxxxjxxxxooooooooooooox:|o@@@@@@@@@@ooo@@@@@o@oo@@@@ggguxj:::::jjj:::::: : ::</text>
  <text x="28" y="476.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::xooo@oxjjjjjjjuugooooooooxoo@@ooojxooxoooooxjxo@@|jjjxxxjjjxxxxxxxoooooooooooox: |o@@@@@@@@@@@oo@@@@@@o@@@@@@@@@@@@g/;:::j::::::::   :</text>
  <text x="28" y="485.79999999999995" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::xoooooxjjjxxoxxooo@@@ooooo@o@o@oxjxwuooooxxxxxo@@ojjjxxxxjjxxxxxxxxooooooooooxj:_oo@@@@@@@@@@@@o@@@@oooo@@@@@@@@@@@@@@gg/jj:::::: : :</text>
  <text x="28" y="495.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  ::::xoo@ooojjg@ooxxo@ooo@@o@@o@@@oooxxxxoo@ooxxxoo@o@@|jjxxxxxxxxooooooxoooooooooxj:|o@@@@@@@@@@@@@@@@@@ooooo@@@@@@@@o@@@@@@@@g/;:::::   :</text>
  <text x="28" y="505" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   :::xooooooooo@oojxo@@ooo@o@o@@@@ooxxjuo@oo@@oxxooo@@@oxxxxoooooooooooooxooooooooxxxo@o@@@@@@@@@@@@@@@@@ooxooo@@@@@oo@@@@@@@@@@@g;::::</text>
  <text x="28" y="514.5999999999999" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   :::xooooooooo@@oxx@@@oooo@@@@@@oooxjxo@@@oo@oogo@o@o@@gooooooooooooooooxxxooooooooxo@@@@o@@@@@@@o@@@@@oooooo@@@@ooo@@@@@@@@@@@@@|;:::</text>
  <text x="28" y="524.2" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   ::jxooxxoooooo@@gx@@@@ooooo@@@@@oxjjjjjv-o@o@oo@o@@@@@@@oooooooooooooooxxxxxoooo@xxo@@@@@@@@@ooj|@@@@ooooooo@@@ooo@@@@@@@@@@@@@@@/::</text>
  <text x="28" y="533.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   : |xoxjjaooxxxxg@o@@@@ooooo@@@@oooxxxjxu:_go@@o@o@oo@@@@@oooooooooooooooxxxxxg@@oxxo@@@@o@ooo@gu@@@@@ooooo@@@oooo@@@@@@oo@@@@@@@@@/j::::</text>
  <text x="28" y="543.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">    :jxxxjjjaooxoyiq@@@@@@ooooo@@@@ooooxxuoo@oo@@oo@@@o@@@@@@oooooooooooxxxxxgg@@@@oxo@@@@@@oo@ooo@@@@@oooooo@@ooxxo@@@@@o@@@@@@@@@@@@|::::</text>
  <text x="28" y="553" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">     jxxxxjjjxoooxj|q@@@@@o@oooo@@@oooooo@@@@o@@@o@o@ooo@@@@@@@oooooooxxxxgg@@@@@@o|jo@@@@@@oooo@@oo@@@oooo@@@ooxxo@@@@@o@@@@@@@@@@@@@|</text>
  <text x="28" y="562.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   :::xxxxxxxjxoooj:|o@@@@@ooooo@@oooxa@oo@@@@o@@o@@@@oo@@@@@@@@@ooooogo@@@@@@@@oo@cxo@@@@@@oo@ogo@@o@ooooo@@@oxxo@@@@@o@@@@@@@@@@@@@@|:</text>
  <text x="28" y="572.1999999999999" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">    :jjxoooooxxxooyj:|@@@@@@ooooo@@xjjjo@o@@o@@@@o@o@ooo@o@o@@@@oooooo@@@@@@@@@oo@ojxo@@@@@@oox@@@@@@ooxoo@@@oxjxo@@@oo@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="581.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">    |jjjxoooooogxoo|:|o@@@@@@oooo@@oj:j|@@o@@@@o@o@@oooo@oo@o@@@ooooooo@@@@@@@ooo@|jo@@@@@@@ooxo@@@@@oxoo@@@oojxo@@@oo@@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="591.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">    jjjjxo@ooooooooo|:o@@@@@@ooooo@oxjjjo@o@@@@o@@@@@ooo@oo@oo@@@@oooooooo@@@ooo@oxxo@@@@@@@@oooo@@@oxoo@@@ooxjxo@@oo@@@@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="601" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   :jjxxxxo@@ooooooo|:|@@@@@@ooxoo@@oxjj|@@@@@@oo@@@oooo@@o@@ooo@@@@@@@@@@@oooo@oojxo@@@o@o@@ooo@@@oooo@@@@oojjo@o@o@@@o@oo@@@@@@@@@@@@@|</text>
  <text x="28" y="610.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   |jjjjxooo@@@@ooooxcio@@@@@ooxooo@ooxjjo@@@@@o@@@@oooo@@oo@@ooo@@@@@@@@o@oooo@o|jx@@@@@ooo@@ooo@oooo@@@@oojjxo@@o@@@ooo@@@@@@@@@@@@@@@|</text>
  <text x="28" y="620.1999999999999" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">   jxjjjx@oooo@@o@oooxjx@@@@@@ooxoo@@ooxx|@o@oo@@@@@oooo@@oo@@ooo@@@@@@@@@oooo@@o|xo@@@@oooooo@oo@ooo@@@@ooxjjo@o@ooooo@@@@@@o@@@@@@@@@@|</text>
  <text x="28" y="629.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">  jjxxjjjao@ooo@@@oooxjuo@@@@oooxoxo@@oopi@@@@@@@@@@oooo@@oo@@@oo@@@@@@@ooooo@@ooxxo@@@@@o@ooooo@ooo@@@@@oxj:xo@@oooooooooooo@@@@@@@@@@@|</text>
  <text x="28" y="639.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> jjjjxxxjjxao@ooo@@ooxjjo@@@@@ooxoxxooooo;|@o@@@@@@ooooo@@@o@@@@oo@@@@@o@oooo@o@oxxo@@@@o@ooooo@oo@@@@@oooj:|g@@@ooooooooo@@@@@@@@@@@@@@|</text>
  <text x="28" y="649" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> xjjjxxxxxxxxoo@ooo@oy:!xo@@@@ooxxxooooo@||@@@@@@@@ooooo@@@oo@@@ooo@@@@ooooo@@o@pjxo@@@@ooooooo@o@o@o@o@oggg@@@@poxooooo@@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="658.6" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> |xjjjxxoooxxxxoo@@oooj:|o@@@@@ooxxoxxxxoo|o@o@@@@@ooooo@@@oo@@@@oo@o@oooooo@o@oxxoo@@o@@gooooooooooooo@@@@@@@@@|jxooooo@@@@@@@@@@@@@@@@@||</text>
  <text x="28" y="668.1999999999999" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> |xxxjjxxooooooooooo@o/.|xo@@@@oooxxxxxxooc|@@@@@o@o@oo@@@@@o@@@@@o@ooooooo@@@@oxxoo@ooooo@ooooxxxxoooo@o@@@@@@@xoooooo@@@@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="677.8" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> |jxoxxxxxxoo@@ooooooooujxo@@@@ooooxxxxxoo||o@@@@@@@o@oo@@@@o@@@@@@o@oooooo@o@opjxoo@oooooooo@ooxxxoooo@@@@@@@@pooooooooo@@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="687.4" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8"> jjjxoooxxxxxxoo@@@@oooxjxoo@@@oooxxxxxxoox:|@@@o@@o@oo@@@o@o@@@@@o@ooooooo@@@oxjxooooooxxooooooxxxooooo@@@@@@|!xooooooo@@@@@@@@@@@@@@@@@@|</text>
  <text x="28" y="697" fill="#c9d1d9" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="8">|::jjaooooooxxxxo@@@o@oojioo@@@oooxxxxxxooo:|@@o@@@o@ooo@@o@@@@@@@oooooooo@o@@oxxxooooooooooooooooxoooo@o@@@@@|joooxooo@@@@@@@@@@@@@@@@@@| _</text>
  <text x="732" y="259" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#3d444d">─</tspan><tspan fill="#58a6ff"> JOhnsonKC201@github </tspan><tspan fill="#3d444d">────────────────────────────────────</tspan></text>
  <text x="732" y="279" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. Uptime: </tspan><tspan fill="#484f58">..............................</tspan><tspan fill="#c9d1d9"> 2 years, 30 days</tspan></text>
  <text x="732" y="299" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. Location: </tspan><tspan fill="#484f58">...............................</tspan><tspan fill="#c9d1d9"> Baltimore, MD</tspan></text>
  <text x="732" y="319" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. Company: </tspan><tspan fill="#484f58">......................</tspan><tspan fill="#c9d1d9"> Morgan State University</tspan></text>
  <text x="732" y="339" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. Languages: </tspan><tspan fill="#484f58">.......</tspan><tspan fill="#c9d1d9"> Python, JavaScript, Jupyter Notebook</tspan></text>
  <text x="732" y="379" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#3d444d">─</tspan><tspan fill="#58a6ff"> Contact </tspan><tspan fill="#3d444d">────────────────────────────────────────────────</tspan></text>
  <text x="732" y="399" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. GitHub: </tspan><tspan fill="#484f58">.......................</tspan><tspan fill="#c9d1d9"> github.com/JOhnsonKC201</tspan></text>
  <text x="732" y="439" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#3d444d">─</tspan><tspan fill="#58a6ff"> GitHub Stats </tspan><tspan fill="#3d444d">───────────────────────────────────────────</tspan></text>
  <text x="732" y="459" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. Repos: </tspan><tspan fill="#484f58">..............</tspan><tspan fill="#79c0ff"> 29</tspan><tspan fill="#3d444d"> | </tspan><tspan fill="#ffa657">. Stars: </tspan><tspan fill="#484f58">..............</tspan><tspan fill="#79c0ff"> 12</tspan></text>
  <text x="732" y="479" font-family="'Consolas', 'Menlo', 'DejaVu Sans Mono', monospace" xml:space="preserve" font-size="16"><tspan fill="#ffa657">. Commits: </tspan><tspan fill="#484f58">...........</tspan><tspan fill="#79c0ff"> 594</tspan><tspan fill="#3d444d"> | </tspan><tspan fill="#ffa657">. Followers: </tspan><tspan fill="#484f58">...........</tspan><tspan fill="#79c0ff"> 6</tspan></text>
</svg>
The fastest way to reach me is email: **[johnsonkc201@gmail.com](mailto:johnsonkc201@gmail.com)**
I am also on [LinkedIn](https://www.linkedin.com/in/johnsonkc).


<img width="1317" height="728" alt="dark_mode" src="https://github.com/user-attachments/assets/c87c9690-62b6-4b3a-91a0-253f57166be6" />

