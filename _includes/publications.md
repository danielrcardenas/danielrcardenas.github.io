<!-- <h1 id="publications"></h1>

<h2 style="margin: 60px 0px 10px;">Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=4DbuyrgAAAAJ&hl=en" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp><temp style="font-size:15px;">[</temp><a href="https://dblp.org/pid/222/6222.html" target="_blank" style="font-size:15px;">DBLP</a><temp style="font-size:15px;">]</temp></h2>

<ul style="margin:0 0 8px;">
<li><strong><span style="color: #13825d">[MSR'25]</span></strong> <strong> SnipGen: A Mining Repository Framework for Evaluating LLMs for Code.</strong>
 <br/><strong>Daniel Rodriguez-Cardenas</strong>, Alejandro Velasco, and Denys Poshyvanyk. 
 <br/><em>Proceedings of the IEEE/ACM 47th International Conference on Software Engineering.</em> 
</li>
</ul>

<ul style="margin:0 0 8px;">
<li><strong><span style="color: #13825d">[ICST'25]</span></strong> <strong> Testing Practices, Challenges, and Developer Perspectives in Open-Source IoT Platforms.</strong>
 <br/><strong>Daniel Rodriguez-Cardenas</strong>,Safwat Ali Khan, Prianka Mandal, Adwait Nadkarni, Kevin Moran, and Denys Poshyvanyk.
 <br/><em>Proceedings of the 18thIEEE International Conference on Software Testing, Verification and Validation.</em> 
</li>
</ul>
<ul style="margin:0 0 8px;">
<li><strong><span style="color: #13825d">[preprint]</span></strong> <strong> On Explaining (Large) Language Models For Code Using Global Code-Based Explanations.</strong>
 <br/>David N. Palacio, Dipin Khati, <strong>Daniel Rodriguez-Cardenas</strong>,Alejandro Velasco, and Denys Poshyvanyk. 
</li>
</ul>

<ul style="margin:0 0 8px;">
<li><strong><span style="color: #13825d">[ICSE'25-NIER]</span></strong> <strong> How Propense Are Large Language Models at Producing Code Smells? A Benchmarking Study.</strong>
 <br/>Alejandro Velasco, <strong>Daniel Rodriguez-Cardenas</strong>, David N. Palacio, Luftar Rahman Alif, and Denys Poshyvanyk. 
 <br/><em>Proceedings of the 47th IEEE/ACM International Conference on Software Engineering.</em>
</li>
</ul>

<ul style="margin:0 0 8px;">
<li><strong><span style="color: #13825d">[ICSE'24-NIER]</span></strong> <strong> Which Syntactic Capabilities Are Statistically Learned by Masked Language Models for Code?.</strong>
 <br/>Alejandro Velasco, <strong>Daniel Rodriguez-Cardenas</strong>, David N. Palacio, and Denys Poshyvanyk. 
 <br/><em>Proceedings of the 46th IEEE/ACM International Conference on Software Engineering.</em>
</li>
</ul>

<ul style="margin:0 0 8px;">
<li><strong><span style="color: #13825d">[ICSME'23]</span></strong> <strong> Benchmarking Causal Study to Interpret Large Language Models for Source Code.</strong>
 <br/> <strong>Daniel Rodriguez-Cardenas</strong>, David N. Palacio, and Denys Poshyvanyk. 
 <br/><em>Proceedings of the 39th International Conference on Software Maintenance and Evolution.</em>
</li>
</ul>



**Yan, Y.**, Cooper, N., Moran, K., Bavota, G., Poshyvanyk, D., and Rich, S., “Enhancing Code Understanding for Impact Analysis by Combining Transformers and Program Dependence Graphs”, in Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE’24), Porto de Galinhas, Brazil, July 15-19, 2024.

**Yan, Y.**, Cooper, N., Chaparro, O., Moran, K., and Poshyvanyk, D., “Semantic GUI Scene Learning and Video Alignment for Detecting Duplicate Video-based Bug Reports”, in Proceedings of the 46th IEEE/ACM International Conference on Software Engineering (ICSE’24), Lisbon, Portugal, April 14-20, 2024

**Yan, Y.**, “On Improving Management of Duplicate Video-Based Bug Reports”, in Proceedings of the 46th IEEE/ACM International Conference on Software Engineering (ICSE’24), Doctoral Smposium, Lisbon, Portugal, April 14-20, 2024

Chen, A., **Yan, Y.**, and Poshyvanyk, D. “ACER: An AST-based Call Graph Generator Framework”, in Proceedings of the 23rd International Working Conference on Source Code Analysis and Manipulation (SCAM’23), Bogotà, Colombia, October 2-3th, 2023 -->




<h2 style="margin: 60px 0px 10px;">Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=4DbuyrgAAAAJ&hl=en" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp><temp style="font-size:15px;">[</temp><a href="https://dblp.org/pid/222/6222.html" target="_blank" style="font-size:15px;">DBLP</a><temp style="font-size:15px;">]</temp></h2>
<div class="publications">
<ol class="bibliography">
{% for link in site.data.publications.main %}
<li>
<div class="pub-row">
 <!-- <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
            <abbr class="badge">{{ link.conference_short }}</abbr>
  </div>-->
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}"><strong><span style="color: #13825d">[{{link.conference_short}}] </span></strong>{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.journal }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Dataset</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>
{% endfor %}

<!-- <li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    <img src="https://img.yliu.me/teaser/MTL_CVPR.png" class="teaser img-fluid z-depth-1">
            <abbr class="badge">CVPR</abbr>
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="https://openaccess.thecvf.com/content_CVPR_2019/html/Sun_Meta-Transfer_Learning_for_Few-Shot_Learning_CVPR_2019_paper.html">Meta-Transfer Learning for Few-Shot Learning</a></div>
      <div class="author">Qianru Sun*, <strong>Yaoyao Liu*</strong>, Tat-Seng Chua, Bernt Schiele <br> (* Equal contribution)</div>
      <div class="periodical"><em>IEEE/CVF Conference on Computer Vision and Pattern Recognition <strong>(CVPR)</strong>, 2019.</em>
      </div>
    <div class="links">
      <a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Meta-Transfer_Learning_for_Few-Shot_Learning_CVPR_2019_paper.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      <a href="https://github.com/yaoyao-liu/meta-transfer-learning" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      <a href="https://lyy.mpi-inf.mpg.de/mtl/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      <a href="https://dblp.uni-trier.de/rec/conf/cvpr/SunLCS19.html?view=bibtex" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
<br>
<strong> <a style="color:#e74d3c; font-weight:600" href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Uf9GqRsAAAAJ&citation_for_view=Uf9GqRsAAAAJ:bEWYMUwI8FkC"><i id="total_citation_mtl">800+</i><i style="color:#e74d3c; font-weight:600"> Citations • </i></a><a href="https://github.com/yaoyao-liu/meta-transfer-learning" target="_blank" rel="noopener"><i style="color:#e74d3c; font-weight:600" id="githubstars_mtl">600+</i><i style="color:#e74d3c; font-weight:600"> GitHub Stars</i></a> <a style="color:#e74d3c; font-weight:600" href="https://www.comp.nus.edu.sg/news/2019-cvpr-research/">• <i>Featured in NUS News</i></a></strong>
<br>
<strong><a style="color:#e74d3c; font-weight:600" href="https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=FXe-a9w0eycJ.2024&vq=en&cstart=60"><i>Top 100 Most Cited CVPR Papers over the Last Five Years</i></a></strong>
  <script>
  githubStars("yaoyao-liu/meta-transfer-learning", function(stars) {
  var startext = document.getElementById("githubstars_mtl");
        startext.innerHTML=stars;
  });
  </script>-->
  <script>
      $(document).ready(function () {
          
          var gsDataBaseUrl = 'https://raw.githubusercontent.com/danielrcardenas/danielrcardenas.github.io/refs/heads/master'
          
          $.getJSON(gsDataBaseUrl + "google-scholar-stats/gs_data.json", function (data) {
              var totalCitation = data['publications']['4DbuyrgAAAAJ:8k81kl-MbHgC']['num_citations']
              document.getElementById('total_citation_mtl').innerHTML = totalCitation;
              var citationEles = document.getElementsByClassName('show_paper_citations')
              Array.prototype.forEach.call(citationEles, element => {
                  var paperId = element.getAttribute('data')
                  var numCitations = data['publications'][paperId]['num_citations']
                  element.innerHTML = '| Citations: ' + numCitations;
              });
          });
      })
  </script>
 

</ol>
</div>




