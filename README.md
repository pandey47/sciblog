A Post with the appearance of a scientific Latex paper.
==================

We need to install django, django-toolbelt and South:

	$ apt-get install -y libpq-dev python-dev
	$ pip install django django-toolbelt south

NOTE: django version must be 1.7. To see your django version:

	$ pip list
To downgrade your django version:
	
	$ pip install -U "django<1.8"



==================================================
        <div class="six columns content">
<div class="section" style="margin-top:0px"> Introduction</div>
<p class="no-indent">
A scientific paper usually consist on 4 or more big sections: introduction, content, conclusions and references.
</p>
<p>
The introduction initially states the problem the scientist wants to address and introduces relevant information to the reader. Usually inside the introduction, or separated as a new section, the scientist summarizes the related work or state of the art. After the state of the art the scientist gives a brief explanation to the technique he or she proposes and what is the <i>contribution</i> to science or the new discovery made. This brief explanation introduces the next section: the content.
</p>
<div class="section"> Content of the Paper</div>
<p>
The content of the paper can be divided into one or several sections or subsections, each of them addressing a part of the scientific discovery.
</p>
<div class="subsection"> Contributions to Science</div>
<p>
There is a common feature to all scientific papers ever published, they all have a contribution to science. It can be a great contribution like
</p>
</div>
<div class="six columns content">
<p class="no-indent">
Einstein's relativity [1] or a small one like Fierro PhD thesis [2]. However all of them make a step further in the path of science.
</p>
<p>
 The numbers inside the square brackets are called the references, which has a different section located always at the end of the document. The references are very important in science since it helps us to cite other authors and relate our work to theirs.
</p>
<div class="section"> Conclusions and Future Work</div>
<p>
The conclusions summarize the main aspects of the paper. Sometimes here can be included the future developments the researcher wants to perform. It may also include the acknowledgements.
</p>
<p>
The author would like to thank José Ignacio Fernández, CTO of Traity, in which code and idea is based this Post [3].
</p>
<div class="section">References</div>
<div class="references">
<li> A. Einstein and A.H. Taub, "The Meaning of Relativity", <i>American Journal of Physics</i>, vol. 18, num. 3, pp. 403-404, 1950.
</li>
<li> M. González-Fierro, "Humanoid Robot Control of Complex Postural Tasks Based on Learning From Demonstrations", PhD. Thesis, 2014.
</li>
<li> J.I. Fernández, "A Scientific Paper Approach to a Personal Web Page", <a href="http://jose.sh/">http://jose.sh/</a>
</li>
</div>
</div>
