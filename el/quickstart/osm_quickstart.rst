����������: Hamish Bowman
������: osgeo-live4.0
 �����: Creative Commons

.. _osm-quickstart:
 
.. image:: images/project_logos/logo-osm.png
  :scale: 100 %�������:100%
  :alt: project logoalt:�������� ��� ��������
  :align: right��������: �����
  :target: http://www.osm.org


************************
���������� �������� ��������� OpenStreetMap 
************************

�����������
========

JOSM
~~~~

**JOSM** (Java OpenStreetMap Editor) ����� ���� editor ��� �� OpenStreetMap (OSM)
��������� �� Java. � �������� ������ ����������� �������� GPX tracks,
GPX track �������� ��� OSM ���� ��������� ��� ���������� �������,�������� �������� ��� �������� ������������� ��� ��� OSM ���� ���������.

* ������ ������: http://josm.openstreetmap.de

� ������� JOSM �� �� �������� �������� ������������ �� �������� �������� ��������:

* agpifoj	     - ���������� ��� ��� ������� �� �������������� �������.
* colorscheme	     - ��������� �� ���������� ������������ ���������� ����������.
* livegps	     - ����������� �������� ������� ��� live GPS ��������� �� �������� gpsd.
* measurement	     - ��������� dialog ��� ������� ��� �� ������� ������ ��� ������ ��� ��������� ��� ���������� measurement paths.
* openvisible	     - ��������� �� ������� ������� gpx ��� osm �� ����� ���������� �� �������� ����� ������� ������.
* slippymap	     - ������������ ��� ������������ ������� ����� ��� JOSM.
* surveyor	     - ��������� ��� �������� ��������/������ �� ��������� ������ gps.
* utilsplugin	     - �������� ���������� �����������.
* validator	     - ����������� ���������.
* wmsplugin	     - ����������� ������� ������ ��� ����������� ���� WMS.


��������� ������
---------------

* ����������� ���������� ������: http://www.use-it.be/europe/docs/OSMmanual/
* ������ ������: http://wiki.openstreetmap.org/wiki/JOSM/Guide
* E����������� ������ <http://showmedo.com/videotutorials/video?name=1800050&amp;fromSeriesID=180>`_
* ������� ������ �������� ��������� �� ����:�����:`File --> Open... --> /usr/local/share/osm/Barcelona.osm.bz2`
* ��������� Further ������� �������� ���� ������� ��� ��������.


Merkaartor
~~~~~~~~~~

**Merkaartor** ����� ��� �������� �������� ����� ��� �� OpenStreetMap �� ����� ������������ �� Qt toolkit.
����� ���� ��� ������ ��� ������ ��� �� JOSM, ���� ���� �������� ��������������.

* ������ ������: http://merkaartor.be
* ����������� �������: http://www.merkaartor.org/Documentation/


Gosmore
~~~~~~~

�� **Gosmore**����� ��� ��������� ����������� ��� OpenStreetMap, �������� ������� ���������, and search client
with support for speech synthesis and fetching the current user's
current GPS location using `gpsd <http://gpsd.berlios.de>`_.

* ������ ������: http://wiki.openstreetmap.org/index.php/Gosmore
* ����������� ������� wiki : http://wiki.openstreetmap.org/wiki/Gosmore#User_Interface
* ���� ������ �� Gosmore �� ������ �� ����������� ��� `planet-*.osm` ������ ���������. ������ �������� ���������� ���� �������� `/usr/local/share/osm/` .

�������� �� �� �������� ��:

::

  bzip2 -dc /usr/local/share/osm/Barcelona.osm.bz2 | gosmore rebuild

���� �� ������������ �� gosmore.pak.


Osmarender
~~~~~~~~~~

��**Osmarender** ����� ��� is a rule-based �������� ������������� ��� �� ���������� SVG ������� ��� �������� OSM. ���������� ��� �������� ������� ��� ������ ��������� OpenStreetMap ��� ��� rules file.
������� ��� SVG ������ � ����� ����� marked up �� �������� �� �� ���� ��� ������������ ��� rule file.

* ������ ������: http://wiki.openstreetmap.org/wiki/Osmarender

����������:

.. ��������: ���� ������� �������  1 GB �������� RAM ��� ������� ������� ������ ��� �� ������������ �������� ����.
   the full city. ��� ���� ����� � �������� �� ���� ����������� ������������.
   ����� `Xapi <http://wiki.openstreetmap.org/wiki/Xapi>`_ ��� OSM Wiki ���
   ������������ ������� �� �� ��� �� ���������� ��������� �������� �� ��� ``.osm`` ������, � ��� �� ��������������� �� 
   *JOSM* � �� *Merkaartor*��� �� ���������� ��������� ��������.

::

  cp /usr/local/share/osm/Barcelona.osm.bz2 .
  bzip2 -d Barcelona.osm.bz2
  osmarender Barcelona.osm

�������� �� ����� �� ������������ �� ��� SVG viewer ���� � `Inkscape` � � `Firefox`:

::

  firefox Barcelona.svg


osm2pgsql
~~~~~~~~~

**osm2pgsql**����� ��� ����������� ��������� �� ����� ���������� �������� OpenStreetMap (.OSM) �� ��������� ���� ���� �� ������� �� "����������" ��� (PostGIS). ��������������� ����� ��� ��� ������������ ��� OSM ��������� �� ����� ��� Mapnik, ����� �� Mapnik ����������� ��������� ���� PostgreSQL ��� ������������ ��������, ���� ��� �������� ��'������� �� ������ OSM.

* ������ ������: http://wiki.openstreetmap.org/wiki/Osm2pgsql

