# sarswatishah.github.io
<!DOCTYPE html>
    <!--
    https://sarswatishah.github.io/
Author: Sarswati Shah, sarswatishah@im.unam.mx
Date: Aug 4, 2022
Note: You can redistribute it and/or modify it under the terms of the GNU General Public License
      as published by the Free Software Foundation.
      It is distributed in the hope that it will be useful,
      but WITHOUT ANY WARRANTY; without even the implied warranty of
      MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
      GNU General Public License for more details.

    -->

    <html lang="en">
    <!-- start of head -->
<head>
  <title>Sarswati Shah</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>

  <!-- Continued the ordered list -->
  <style type="text/css">
    ol.split { list-style-type: none; }
    ol.split li:before
    {
      counter-increment: mycounter;
      content: counter(mycounter) ".\00A0\00A0";
    }
    ol.split li
    {
      text-indent: -1.3em;
    }
    ol.start { counter-reset: mycounter; }
    a{TEXT-DECORATION:none}
    body {
      min-height: 75rem;
      padding-top: 4.5rem;
      padding-left: 1rem;
      padding-right: 1rem;
    }
    :target{
      padding-top:4.5rem; /* = to height of navbar */
      margin-top:-4.5rem;
    }
    .navbar {
      padding-left: 1rem;
      padding-right: 1rem;
    }
  </style>
</head>

<!-- end of head -->
<body>
<!-- start of navigation -->
<nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="index.html">Sarswati SHAH's homepage</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarCollapse">
      <ul class="navbar-nav me-auto mb-2 mb-md-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#publication">Publications</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#award" >Awards & Honors</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#conference" >Conferences & Talks</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#teaching" >Teaching</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="files/CV_en.pdf" >CV</a>
        </li>
      </ul>
      <!--<form class="d-flex">-->
        <!--<input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">-->
        <!--<button class="btn btn-outline-success" type="submit">Search</button>-->
      <!--</form>-->
    </div>
  </div>
</nav>

<!-- end of navigation -->
<!-- start of personal -->
<div class="container-fluid">
  <div class="row">
    <!-- Contact Info on the Sidebar -->
    <div class="col-lg-4 col-xl-3">
      <p>
      <!--<img class="img-fluid" src="photo/Ulm.jpg" width="400rem" alt="">-->
      <img class="img-fluid" src="photo/Rhode.jpg" alt="">
      </p>
      <address>
      <strong>Mailing address:</strong><br>
      Office 3, Instituto de Matemáticas<br>
      Universidad Nacional Autónoma de México<br>
      Blvd Juriquilla # 3001, Juriquilla-76230
     Querétaro, México<br>
      <strong>Email:</strong> junming.duan@epfl.ch<br>
      </address>
      <p>
      <!-- Links on the Sidebar -->
      <a href="https://scholar.google.com/citations?user=cK3Xg5wAAAAJ&hl=en" target="_blank"><img src="icons/google-scholar.svg" width="24" height="24"></a> &nbsp;
      <a href="https://www.researchgate.net/profile/Sarswati_Shah" target="_blank"><img src="icons/research-gate.svg" width="24" height="24"></a> &nbsp;
      <a href="https://github.com/JunmingDuan" target="_blank"><img src="icons/Github_Logo.png" width="24" height="24"></a> &nbsp;
      <a href="mailto:sarswatishah@im.unam.mx" target="_blank"><img src="icons/mail.svg" width="26" height="26"></a> &nbsp;
      </p>
    </div>

    <!-- Entries Column -->
    <div class="col-lg-8 col-xl-9">

      <div style="margin-top:0%; text-align:justify;">
        <p>I am a postdoctoral researcher at
        <a href="https://www.epfl.ch/labs/mcss/" style="color:black" target="_blank">MCSS</a>,
        <a href="https://www.epfl.ch/en/" style="color:black" target="_blank">EPFL</a>,
        working with
        <a href="https://people.epfl.ch/jan.hesthaven?lang=en" style="color:black" target="_blank">Prof. Jan S. Hesthaven</a>.
        I received my B.Sc. (2016) and Ph.D. (2021) at
        <a href="https://www.pku.edu.cn/" style="color:black" target="_blank">Peking University</a>,
        in <a href="https://www.math.pku.edu.cn/" style="color:black" target="_blank">School of Mathematical Sciences</a>,
        supervised by <a href="http://dsec.pku.edu.cn/~tanghz/" style="color:black" target="_blank">Prof. Huazhong Tang</a>.
        My research mainly consists of high-order accurate numerical methods
        and reduced-order modeling.
        </p>
      </div>

      <h2>Research Interests</h2>
      <p>
      <ul style="list-style-position:inside;margin:0px;padding:0px;">
        <li>Numerical methods for hyperbolic conservation laws</li>
        <li>Computational fluid dynamics</li>
        <li>High-order accurate numerical methods</li>
        <li>Structure-preserving methods</li>
        <li>Moving mesh methods</li>
        <li>Reduced-order modeling</li>
        <li>Data-driven methods and scientific machine learning</li>
      </ul>
      </p>

      <h2>Education</h2>
      <h5>Ph.D. in Computational Mathematics</h5>
      <p>
      Peking University, China (Sep, 2016 -- Jul, 2021)<br>
      Thesis: Entropy stable numerical methods for special
      relativistic (magneto)hydrodynamics<br>
      Advisor: <a href="http://dsec.pku.edu.cn/~tanghz/" style="color:black">Prof. Huazhong Tang</a>
      </p>

      <h5>B.Sc. in Information and Computing Science</h5>
      <p>
      Peking University, China (Sep, 2012 -- Jul, 2016)<br>
      </p>
    </div>
  </div>
</div>

<!-- end of personal -->
<!-- start of employment -->
<div class="bg-light p-3">
<div class="content-md container-fluid">
<h2 id="employment">Employment</h2>
<ul>
<li><b>Postdoc</b>, MCSS, École Polytechnique Fédérale de Lausanne (EPFL), Switzerland, Sep, 2021 -- present.
 Mentor: <a href="https://people.epfl.ch/jan.hesthaven?lang=en" style="color:black" target="_blank">Prof. Jan S. Hesthaven</a></li>
</ul>

        </div>
    </div>
    <!-- end of employment -->
<!-- start of publication -->
<div class="p-3">
<div class="content-md container-fluid">
<h2 id="publication">Research Publications</h2>

            <h4>Appeared or Accepted</h4>
            <ol class="split start">
        <li>S.T. Li, <b>J.M. Duan</b>, and H.Z. Tang,
High-order accurate entropy stable adaptive moving mesh finite difference schemes for (multi-component) compressible Euler equations with the stiffened equation of state, <i><b>Comput. Methods Appl. Mech. Engrg.</b></i>, 399: 115311, 2022.

 [<a href="https://arxiv.org/abs/2202.07989" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.cma.2022.115311" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
High-order accurate entropy stable adaptive moving mesh finite difference schemes for special relativistic (magneto)hydrodynamics, <i><b>J. Comput. Phys.</b></i>, 456: 111038, 2022.

 [<a href="https://arxiv.org/abs/2107.12027" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.jcp.2022.111038" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
An analytical solution of the isentropic vortex problem in the special relativistic magnetohydrodynamics, <i><b>J. Comput. Phys.</b></i>, 456: 110903, 2022.

 [<a href="https://arxiv.org/abs/2107.01966" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.jcp.2021.110903" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
High-order accurate entropy stable finite difference schemes for the shallow water magnetohydrodynamics, <i><b>J. Comput. Phys.</b></i>, 431: 110136, 2021.

 [<a href="https://arxiv.org/abs/2003.10081" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.jcp.2021.110136" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
Entropy stable adaptive moving mesh schemes for 2D and 3D special relativistic hydrodynamics, <i><b>J. Comput. Phys.</b></i>, 426: 109949, 2021.

 [<a href="https://arxiv.org/abs/2007.12884" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.jcp.2020.109949" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
High-order accurate entropy stable nodal discontinuous Galerkin schemes for the ideal special relativistic magnetohydrodynamics, <i><b>J. Comput. Phys.</b></i>, 421: 109731, 2020.

 [<a href="https://arxiv.org/abs/1911.03825" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.jcp.2020.109731" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
High-order accurate entropy stable finite difference schemes for one- and two-dimensional special relativistic hydrodynamics, <i><b>Adv. Appl. Math. Mech.</b></i>, 12(1): 1-29, 2020.

 [<a href="https://arxiv.org/abs/1905.06092" target="_blank">arXiv</a>][<a href="https://doi.org/10.4208/aamm.OA-2019-0124" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
An efficient ADER discontinuous Galerkin scheme for directly solving Hamilton-Jacobi equation, <i><b>J. Comput. Math.</b></i>, 38(1): 58-83, 2020.

 [<a href="https://arxiv.org/abs/1901.10228" target="_blank">arXiv</a>][<a href="https://doi.org/10.4208/jcm.1902-m2018-0189" target="_blank">journal</a>]
</li>
<li>D. Ling, <b>J.M. Duan</b>, and H.Z. Tang,
Physical-constraints-preserving Lagrangian finite volume schemes for one- and two-dimensional special relativistic hydrodynamics, <i><b>J. Comput. Phys.</b></i>, 396: 507-543, 2019.

 [<a href="https://arxiv.org/abs/1901.10625" target="_blank">arXiv</a>][<a href="https://doi.org/10.1016/j.jcp.2019.06.055" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b> and H.Z. Tang,
A second-order accurate scheme for a kinetic equation of two-dimensional Vicsek swarming model, <i><b>Nat. Sci. J. Xiangtan Univ.</b></i>, 41(1): 1-14, 2019.
 (in Chinese)
[<a href="http://www.jxtu.net/xtdxxbzr/ch/reader/view_abstract.aspx?file_no=201901001&flag=1" target="_blank">journal</a>]
</li>
<li><b>J.M. Duan</b>, Y.Y. Kuang, and H.Z. Tang,
Model reduction of a two-dimensional kinetic swarming model by operator projections, <i><b>East Asian J. Appl. Math.</b></i>, 8(1): 151-180, 2018.

 [<a href="https://arxiv.org/abs/1701.02888" target="_blank">arXiv</a>][<a href="https://doi.org/10.4208/eajam.170617.141117a" target="_blank">journal</a>]
</li>
                    </ol>

                <h4>Preprints</h4>
                <ol class="split">
            <li><b>J.M. Duan</b>, Q. Wang, and J.S. Hesthaven,
Machine learning enhanced aerodynamic forces prediction based on sparse pressure sensor inputs,  submitted to <i><b>AIAA J.</b></i>, 2023.

 [<a href="https://arxiv.org/abs/2305.09199" target="_blank">arXiv</a>]</li>
<li>J. Wang, <b>J.M. Duan</b>, Z.W. Ma, and W. Zhang,
An adaptive moving mesh finite difference scheme for tokamak magneto-hydrodynamic simulations,  submitted to <i><b>Comput. Phys. Commun.</b></i>, 2023.

</li>
<li>Z.H. Zhang, <b>J.M. Duan</b>, and H.Z. Tang,
High-order accurate well-balanced energy stable adaptive moving mesh finite difference schemes for the shallow water equations with non-flat bottom topography,  submitted to <i><b>J. Comput. Phys.</b></i>, 2023.

 [<a href="https://arxiv.org/abs/2303.06924" target="_blank">arXiv</a>]</li>
<li><b>J.M. Duan</b> and J.S. Hesthaven,
Non-intrusive data-driven reduced-order modeling for time-dependent parametrized problems,  submitted to <i><b>J. Comput. Phys.</b></i>, 2023.

 [<a href="https://arxiv.org/abs/2303.02986" target="_blank">arXiv</a>]</li>

        </div>
    </div>
    <!-- end of publication -->
<!-- start of award -->
<div class="bg-light p-3">
<div class="content-md container-fluid">
<h2 id="award">Awards & Honors</h2>
<ul>
<li><b>Outstanding Graduate of Peking University</b>, Peking University, Jul, 2021.
</li>
<li><b>National Scholarship for Graduate Student</b>, Chinese Ministry of Education, Dec, 2020.
</li>
<li><b>Merit Student of Peking University</b>, Peking University, Oct, 2020.
</li>
<li><b>The First Prize in Outstanding Youth Paper Award of Beijing Society of Computational Mathematics</b>, Beijing Society of Computational Mathematics, Aug, 2020.
</li>
<li><b>BICMR Scholarship for Graduate Student</b>, Beijing International Center for Mathematical Research (BICMR), Peking University, 2019--2020.
</li>
<li><b>President Scholarship for PhD Student</b>, Peking University, 2018--2020.
</li>
<li><b>Founder Scholarship</b>, Peking University, Sep, 2019.
</li>
<li><b>DTZ Cushman & Wakefield Scholarship</b>, Peking University, Sep, 2017.
</li>
<li><b>Outstanding Undergraduate of Peking University</b>, Peking University, Jul, 2016.
</li>
</ul>

        </div>
    </div>
    <!-- end of award -->
<!-- start of conference -->
<div class="p-3">
<div class="content-md container-fluid">
<h2 id="conference">Conferences & Talks</h2>
<ul>
<li><b>ECCOMAS YIC 2023: 7th Young Investigators Conference</b>,
University of Porto, Porto, Portugal, Jun 19-21, 2023.
(Talk: <i>Non-intrusive data-driven reduced-order modeling for time-dependent parametrized problems</i>)
</li>
<li><b>Swiss Numerics Day 2023</b>,
Universität Bern, Bern, Switzerland, Jun 07, 2023.
(Talk: <i>Machine learning enhanced aerodynamic forces prediction based on sparse pressure sensor inputs</i>)
</li>
<li><b>MATHICSE Retreat</b>,
Bienne, Switzerland, Jun 05-06, 2023.
(Talk: <i>Machine learning enhanced aerodynamic forces prediction based on sparse pressure sensor inputs</i>)
</li>
<li><b>Invited talk to the Oberseminar host by Prof. Christian Klingenberg</b>,
online, Nov 17, 2022.
(Talk: <i>Data-driven reduced-order modeling for time-dependent parametrized problems</i>)
</li>
<li><b>MultiMat 2022: 10th International Conference on Numerical Methods for Multi-Material Fluid Flow</b>,
Universität Zürich, Zürich, Switzerland, Aug 22-26, 2022.
(Talk: <i>High-order accurate entropy stable adaptive moving mesh methods</i>)
</li>
<li><b>MATHICSE Retreat</b>,
Villars-sur-Ollon, Switzerland, Jun 27-29, 2022.
(Talk: <i>High-order accurate entropy stable adaptive moving mesh methods</i>)
</li>
<li><b>Symposium on High-Fidelity Numerical Simulation of Fluid Problems</b>,
Peking University, Beijing, China, Jun 05-07, 2021.
(Talk: <i>Entropy stable schemes for RHD</i>)
</li>
<li><b>Forum of Numerical Methods and Applications in Fluids</b>,
Xiangtan University, Xiangtan, China, Dec 11-13, 2020.
(Talk: <i>Entropy stable adaptive moving mesh schemes for RHD</i>)
</li>
<li><b>Student Forum of Chinese Society of Industrial and Applied Mathematics</b>,
online, Nov 14-15, 2020.
(Talk: <i>Entropy stable adaptive moving mesh schemes for RHD</i>)
</li>
<li><b>The National Mechanics Graduate Student Forum</b>,
Peking University, Beijing, China, Nov 06-08, 2020.
(Talk: <i>High-order entropy stable DG schemes for RMHD</i>)
</li>
<li><b>Selection of Excellent Young Scholar's paper of Beijing Society of Computational Mathematics</b>,
online, Aug 30, 2020.
(Talk: <i>PCP Lagrangian scheme for RHD. The first prize.</i>)
</li>
<li><b>Trends of High-Order Numerical Methods for Computational Fluid Dynamics and Their Applications</b>,
Beijing, China, Jan 10-13, 2020.
(Attended)
</li>
<li><b>Annual Meeting on High Resolution Method for Multi-Material Hydrodynamics of Science Challenge Project</b>,
Xiamen University, Xiamen, China, Nov 29-Dec 01, 2019.
(Talk: <i>PCP Lagrangian scheme for RHD</i>)
</li>
<li><b>Sino-German Workshop on Advanced Numerical Methods for Hyperbolic Balance Laws</b>,
Beijing Institute of Applied Physics and Computational Mathematics, Beijing, China, Sep 25-27, 2019.
(Attended)
</li>
<li><b>Workshop on Numerical Methods for Complex Physical Problems</b>,
Nanjing University of Aeronautics and Astronautics, Nanjing, China, Aug 28-30, 2019.
(Talk: <i>High-order entropy stable finite difference schemes for RHD</i>)
</li>
<li><b>The 12th National Annual Meeting of Computational Mathematics</b>,
Harbin, China, Jul 31-Aug 04, 2019.
(Talk: <i>High-order entropy stable finite difference schemes for RHD</i>)
</li>
<li><b>Graduate Student Forum of Chinese Society of Industrial and Applied Mathematics</b>,
Academy of Mathematics and System Science, Chinese Academy of Science, Beijing, China, Jun 22, 2019.
(Talk: <i>PCP Lagrangian scheme for RHD</i>)
</li>
<li><b>Annual Meeting of Center for Applied Physics and Technology</b>,
Peking University, Beijing, China, Dec 13, 2018.
(Talk: <i>PCP Lagrangian scheme for RHD</i>)
</li>
<li><b>Annual Meeting of Science Challenge Project</b>,
Jilin University, Changchun, China, Nov 17-19, 2018.
(Poster: <i>PCP Lagrangian scheme for RHD</i>)
</li>
<li><b>Beijing Seminar on Computational Fluid Dynamics</b>,
Beijing Institute of Applied Physics and Computational Mathematics, Beijing, China, Nov 11, 2018.
(Talk: <i>PCP Lagrangian scheme for RHD</i>)
</li>
<li><b>The 16th Annual Meeting of Chinese Industrial and Applied Mathematics</b>,
Chengdu, China, Sep 13-16, 2018.
(Attended)
</li>
<li><b>The 2nd Workshop on Simulation and Algorithm for Complex Physical Problems</b>,
Xiangtan University, Xiangtan, China, Apr 27-30, 2018.
(Attended)
</li>
<li><b>Annual Meeting of Science Challenge Project</b>,
Xiamen University, Xiamen, China, Nov 10-12, 2017.
(Attended)
</li>
<li><b>The 11th National Annual Meeting of Computational Mathematics</b>,
Xian, China, Jul 21-23, 2017.
(Attended)
</li>
<li><b>The 5th International Conference on Numerical Simulation for Multi-material and Multi-physics Flows</b>,
Beijing Institute of Applied Physics and Computational Mathematics, Beijing, China, Jul 03-07, 2017.
(Attended)
</li>
</ul>

        </div>
    </div>
    <!-- end of conference -->
<!-- start of teaching -->
<div class="bg-light p-3">
<div class="content-md container-fluid">
<h2 id="teaching">Teaching Assistant</h2>
<ul>
<li><b>Analysis III</b>
(undergraduate),
École Polytechnique Fédérale de Lausanne, Fall, 2022.
</li>
<li><b>Advanced Analysis I</b>
(undergraduate),
École Polytechnique Fédérale de Lausanne, Fall, 2021.
</li>
<li><b>Numerical Methods of Partial Differential Equations</b>
(undergraduate and graduate),
Peking University, Fall, 2019.
</li>
<li><b>Linear Algebra B</b>
(undergraduate),
Peking University, Fall, 2018.
</li>
<li><b>Advanced Algebra II</b>
(undergraduate),
Peking University, Spring, 2018.
</li>
<li><b>Linear Algebra B</b>
(undergraduate),
Peking University, Fall, 2017.
</li>
<li><b>Mathematical Modeling</b>
(undergraduate),
Peking University, Spring, 2017.
</li>
<li><b>Partial Differential Equations</b>
(undergraduate),
Peking University, Fall, 2016.
</li>
</ul>

        </div>
    </div>
    <!-- end of teaching -->
<!-- start of supervision -->
<div class="p-3">
  <div class="content-md container-fluid">
    <h2 id="service">Supervision</h2>
    <ul>
      <li><b>Master thesis</b>: Investigation of the aerosol evolution and delivery into the upper airway under transient conditions</li>
      Zacchei Filippo, EPFL (with Prof. Jan S. Hesthaven), Fall, 2022
      <li><b>Master thesis</b>: High-order entropy stable discontinuous Galerkin schemes using artificial viscosity</li>
      Jaugey Louis Vincent Marie, EPFL (with Prof. Jan S. Hesthaven), Fall, 2022
      <li><b>Semester project</b>: Scalable implementation of high-order entropy stable finite difference schemes</li>
      Kovacic Bartul, EPFL (with Prof. Jan S. Hesthaven), Fall, 2022
    </ul>
  </div>
</div>

<!-- end of supervision -->
<!-- start of service -->
<div class="bg-light p-3">
  <div class="content-md container-fluid">
    <h2 id="service">Professional Services</h2>
    <ul>
      <li><b>Reviewer for AMS Mathematical Reviews</b></li>
      <li><b>Referee for the following journals:</b></li>
        <li style="list-style-type:none;">Journal of Computational Physics</li>
        <li style="list-style-type:none;">Journal of Computational and Applied Mathematics</li>
        <li style="list-style-type:none;">Communications in Nonlinear Science and Numerical Simulation</li>
        <li style="list-style-type:none;">International Journal for Numerical Methods in Engineering</li>
        <li style="list-style-type:none;">East Asian Journal on Applied Mathematics</li>
        <li style="list-style-type:none;">Communications in Computational Physics</li>
        <li style="list-style-type:none;">Journal of Scientific Computing</li>
        <li style="list-style-type:none;">International Journal of Computational Methods</li>
    </ul>
  </div>
</div>

<!-- end of service -->
<!-- start of skill -->
<div class="p-3">
  <div class="content-md container-fluid">
    <h2 id="skills">Skills</h2>
    Be familiar with C, C++, MPI, Python, PyTorch, MATLAB, OpenFOAM, PETSc, Linux shell, Fortran, LaTeX
  </div>
</div>

    
<!-- end of skill -->
        </body>

    </html>
