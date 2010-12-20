����������: Stefan Tzeggai
:������: osgeo-live4.0
:����� : Creative Commons

.. _geopublisher-quickstart:
 
.. image:: images/project_logos/logo-Geopublisher.png
  :scale: 100 %
  :alt: project logoalt:
  :align: right
  :target: http://en.geopublishing.org/Geopublisher

***********************
������� �������� ������������ Geopublishe
***********************

Demo-Atlas
==========
* `�� Demo Atlas ����� �� ��� ����������� ��������� ��� ��������� ����� ��� ����� �� ���������-���������� ��������, �������, ��� ������������� ��� ��� ������ 1.5. <file :///usr/share/doc/geopublishing/ChartDemoAtlas_WorkingCopy.zip>

<��������� ��� Geopublisher (���������� ��� ������� �������)
=========
Geopublisher (���������� ��� ������� �������)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* `First "Hands on Geopublisher" tutorial, English, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/tutorial_Geopublisher_1/HandsOn-Geopublisher1_EN.pdf>`_
* `First "Hands on Geopublisher" tutorial, French, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/tutorial_Geopublisher_1/HandsOn-Geopublisher1_FR.pdf>`_
* `Second "Hands on Geopublisher" tutorial, English, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/tutorial_Geopublisher_1/HandsOn-Geopublisher2_EN.pdf>`_
* `Second "Hands on Geopublisher" tutorial, French, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/tutorial_Geopublisher_1/HandsOn-Geopublisher2_FR.pdf>`_

AtlasStyler (�������������� layers with SLD)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* `AtlasStyler Labelling tutorial, English, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/tutorial_AtlasStyler_Labelling/AtlasStyler_v1.3_EN_LabellingTutorial_091012.pdf>`_
* `AtlasStyler tutoriel d'étiquetage SLD, French, ������������� ��� ��� ������ 1.5 <file:///usr/share/doc/geopublishing/tutorial_AtlasStyler_Labelling/AtlasStyler_v1.5_FR_Tutoriel_d_etiquetage_101006.pdf>`_

����������� ��������� ���������� ��� blog`http://en.geopublishing.org <http://en.geopublishing.org">`(������ ������ �� ����� ������������ ��� ��������� ��� �� ������ �� ���������� ���� �� ������. 

���������� ������
=======

Geopublisher (���������� ��� ������� �������)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* `Geopublisher ���������� ������, French, ������������� ��� ��� ������ 1.2 <file:///usr/share/doc/geopublishing/Geopublisher_v1.2_FR_Handbuch_090803.pdf>`_
* `Geopublisher ���������� ������, German, ������������� ��� ��� ������ 1.2 <file:///usr/share/doc/geopublishing/Geopublisher_v1.2_DE_Handbuch_090801.pdf>`_    

AtlasStyler (�������������� layers with SLD)~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
* `AtlasStyler manual, German, ������������� ��� ��� ������ 1.2 <file:///usr/share/doc/geopublishing/AtlasStyler_v1.2_DE_Handbuch_090601.pdf>`_  

 AtlasViewer  (��� �� ���������������� �� �������� ��� �������������� �� �� Geopublisher)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* `AtlasViewer ���������� ������, French, Created for version 1.3 <file:///usr/share/doc/geopublishing/AtlasViewer_v1.3_FR_Manual_090522.pdf>`_
* `AtlasViewer ���������� ������, English, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/AtlasViewer_v1.3_EN_Manual_090522.pdf>`_ 
* `AtlasViewer ���������� ������, German, ������������� ��� ��� ������ 1.3 <file:///usr/share/doc/geopublishing/AtlasViewer_v1.3_DE_Handbuch_090522.pdf>`_  


=======��������� �� ���������

~~~~~~~~~~~~~~~���������� �� ���������

�� ��������� Geopublisher ����� �� ��� end-user �������� � ����� ��������� ��� ������ �� �������� , �� ����������� �� ����������� ��� ��� �� �� ���������� �� ����� �������. �� DVD ���� ������������ ��� ����� ������� demo �����������, �� ����� ������ �� �������������� ��� ���� ��� �� ��������� ������ �� ���� ��� ��������.

0) �� OSGeo Live DVD ������������ �� Xubuntu Operating system�� ����� ���� ��� ����� �������� �� ��� Java-����������� ���������: ��� ���� �������� ������ ���� ���� ���� ����� ����� (���� ���������� �� 'Applications' ���  'Places') ��� ��������  'Customize Panel'. ����, ��������� ��� ������� Autohide' . The menubar is now hidden unless your mouse reaches the top of the screen. 

1) Uncompress the demo atlas: Click on `this link <file:///usr/share/doc/geopublishing/ChartDemoAtlas_WorkingCopy.zip>`_ and select 'Open with Archive Manager (default)'. This will open the ZIP file. Next select the third icon in the toolbar to extract and choose 'Desktop' as the target folder. Now you should have a folder 'ChartDemoAtlas' on your desktop. You can close the Archive Manager application.

3) Now start the Geopublisher application. :menuselection:`Geospatial --> Desktop GIS --> Geopublisher`. Geopublisher starts and will ask you which atlas to open. Select 'atlas.gpa' from folder 'ChartDemoAtlas'. It now loads the atlas. You should see a triparted GUI with a map-pool, data-pool and menu area. This GUI allows you to create and organize multiple multi-language maps.

4) Add a Shapefile to the atlas: Select :menuselection:`File --> Import... --> Import files` and select '/home/user/data/natural_earth/10m_lakes.shp'. Geopublisher will ask you to describe that new layer with a title and a description. If that atlas would be configured to be multilingual, this information would be asked for every language. You will see the new layer appearing the DataPool section.

5) Open the map 'The digital divide' by double-clicking it in the map-pool (top right area). A second window opens. To add the layer to the may, use drag'n'drop: Position the 'Map Composer' windows so that you can still see the DataPool. Click the new layer and hold the left mouse-button. Move the layer into the legend area of the Map Composer window and release it there. Using drag'n'drop you can also change the order of layers in the map. Try out styling the layer with AtlasStyler (tool-icon -> style) and finally close the window.

5) Export the atlas: :menuselection:`File --> Export` and follow the wizard: Export online and offline version of the atlas to a new directory 'Desktop/ChartAtlasExported'. When the export finished, click the "open folder" button. You see the exported and stand-alone versions of the atlas, that you were just editing.

6) Try the exported atlas: Go into the `Desktop/ChartAtlasExported/DISK` folder and run `start.sh`. 

7) Geopublisher has many more possibilities of course. Go to :menuselection:`Applications --> Education --> Geopublishing documentation` and look at all the documentation provided.

8) Have fun and/or please give feedback to tzeggai@wikisquare.de
