����������:Author: Johannes Wilden
:������ Version: osgeo-live4.0
: �����License: Creative Commons
:������������ Thanks: geotools-user list

.. _deegree-quickstart:

******************
deegree Quickstart 
******************

deegree is a Java framework which can be used for setting up web based spatial
data infrastructures.�� ��������� DEEGREE ����� ��� �������� JAVA ��� ������ �� �������������� ���  

This Quick Start describes how to:�� ������������� ������� "�������� �����������" ����������� ���:

  * use the iGeoportal Client��������������� � �������� ��� iGeoportal Client
  * send some example requests to our Services��������� ������ ������������ ��������� ���� ��������� ���

Start deegree�������� ������������ DEEGREE
=============

#. �������� "�������� ������������ deegree" ��� �� ������� �������� �������Choose deegree start from the start menu
#. The application will take a few moments to start up� �������� ���������� ���� ����� ��� �� ���������

Welcome View������ ��������������
============

#. When you start up deegree for the first time the Welcome view takes up the entire display.���� �������� �� ��������� deegree ��� ����� ����, � ������ �������������� ������������ �������� ��� ����� This screen� ����� ����
   has links to tutorials, documentation and the project website.���� ��������� �� ���������, ������� ��� ��� ���������� ��� �����.

You can return to the Welcome view at any time by clicking on "`Start page`" in
the menu on the left side.������ ������ �� ���������� ����������� ������ ���� "<����� ��������������" �������� ���� ���� ��� "������ �������" ���� �������� ���� �������� ������.

Services
========���������

By clicking on "`Services`" in the menu bar on the left side of the welcome
view, a new view will be opened.�������� ���� ��� "���������" ���� ����� ���� �������� ������ ��� ������� ��������������, ��� ��� �������� ������� In the menu bar on the left, you can choose
between "`WMS example requests & clients`", "`WFS example requests & client`"
and "`WCS example requests & client`".���� ����� �������� ������ ������ �� �������� ������ "WMS ������������ ���������&�������" ���  "WFS ������������ ���������&������" ���  "WCS ������������ ���������&������".

Client(iGeoPortal) 
==================������� (iGeoPortal) 


Starting with the deegree welcome view, choose "`Client (iGeoPortal)`" from the
menu bar.������� ��������� �� ��� ������ �������������� ��� deegree, ���������� "`Client (iGeoPortal)`" ��� �� ������� ����� ��������� The next window shows an overview of deegree iGeoPortal.�� ������� �������� ����������� ��� ������ ����� ��� deegree iGeoPortal Click on
"Utah" in the "`deegree iGeoPortal WebMapContexts`" menu on the left side.��� �������� ������� ���� ��� "Utah" ��� ��� ��������  "`deegree iGeoPortal WebMapContexts`"��� ��������� ���� �������� ������. Now
iGeoPortal with the "Utah" WebMapContexts will be loaded.���� �� iGeoPortal �� �� "Utah" WebMapContexts �� �������� On the right side of
the map window, there is a LayerListView, where different layers can be switched
on and off.��� ����� ������ ��� ��������� ��� ����� ������� � ������� ��� LayerListView �� ��� ����� ��������� � ���������� ��� ������ �� �������� ��� ����� ������ ������������ ��������  �� ����� ������ � ��. To see activated layers, you have to refresh the map window with the
"`refresh`" button above the map.��� �� �������� ������� �� ��� �� �������������� ��������, ������ �� �������������� �� ������ ��� "���������" ��� ������� ���� ��� �� �����. It is the leftmost one.����� �� ������������ ����. A menu bar containing
tools for navigating in the map can be found above the map window.� ����� �� �� ����� ��� ������������ �� �������� ��� ��� �������� ��� ����� ��������� ���� ��� �� �������� ��� �����. Click on the
magnifier with the "+" Button and click into the map window, to zoom in.�������� ���� ���� ��������� ��� ����� ��� ������ "+" ��� ��� �������� ���� ��� ����� �������� �� ������� ���������. You can
either use the "hand" Button, to move the map extent.������, �� �� ����� ��� "������" ������ ������ �� ����������� �� ������� ��� ����� ��� ������� ��� ������.


Web Map Service
===============�������� Web Map

Starting on the "`Services`" page mentioned above, you can access the deegree Web
Map Service example requests and clients.���������� �� ������ "���������" ���� ����� ����� ������� ������������, ������ ������ �� ���� �������� ���� �������� deegree Web Mapexample requests ��� clients. ����������� �� "`Basic WMS requests`" ������ ������ �� ��� �� �������� �� ������ requests  ��� deegree WMS ��� �� responses. Choose the "`Basic WMS requests`" to
have a look at the basic requests of the deegree WMS and its responses. 
Clicking on "Generic Client" on the left side starts the deegree Generic OGC
WebService Client to send POST requests to the WMS.�������� ���� ��� "Generic Client" ���� �������� �����, �� deegree Generic OGC
WebService Client ������ �� ������� POST requests ���  WMS.  Choose WMS from the Service
drop down menu and push the "Send" Button on the right side.����������� WMS ��� �� ������������� ����� ��� "Service" ��� �������� �� ������ "Send" ���� ����� ������, 
 � ����������� ������ �� ����� ��� ������ ��� �� ������� �� The Response might
be a picture showing the citelayers below the xml field.

Web Feature Service
====================�������� Web Feature

Starting on the "`Services`" page mentioned above, you can access the deegree
Web Feature Service example requests and clients.���������� �� ������ "���������" ���� ����� ����� ������� ������������, ������ ������ �� ���� �������� ���� �������� dWeb Feature Service example requests and clients. Choose the "`Basic WFS
requests`" to have a look at the basic requests of the deegree WFS and its
responses.����������� �� "`Basic WFS requests`" ������ ������ �� ��� �� �������� �� ������ requests  ��� deegree WFS ��� �� responses.  Clicking on "`Generic Client`" on the left side starts the deegree
Generic OGC WebService Client to send POST requests to the WFS.�������� ���� ��� "Generic Client" ���� �������� �����, �� deegree Generic OGC
WebService Client ������ �� ������� POST requests ���  WFS. Chose utah from
the examples drop down menu and Springs_code5.xml from the Request drop down
menu.��� �������� ������ ������ �� �������� utah ��� �� ������������� ����� ��� "examples" ��� �� ������ Springs_code5.xml ��� �� ������������� ����� ��� "Request". Then push the "Send" button on the right side and ahve a look at the
response below.��� �������� ������ ������ �� ������ �� ������ "Send" ��� ����� ������ ��� �� ��� ��� ����������� ����. 

Web Coverage Service
====================�������� WebCoverage 

Starting on the "`Services`" page mentioned above, you can access the deegree Web
Feature Service example requests and clients.���������� �� ������ "���������" ���� ����� ����� ������� ������������, ������ ������ �� ���� �������� ���� �������� dWeb Feature Service example requests and clients. Choose the "Basic WFS requests" to
have a look at the basic requests of the deegree WFS and its responses.����������� �� "`Basic WFS requests`" ������ ������ �� ��� �� �������� �� ������ requests  ��� deegree WFS ��� �� responses. 

What Next?�� ���������� ��� ��������?
==========

This was just a small overview about deegree services and clients.���� ���� ��� ������� ���������� ��� ������������  deegree services and clients Have a look
into the degree wiki, the deegree online demo and the deegree.org home, to learn
more about further services and functionalities of the deegree framework.��� �� degree wiki,deegree online demo ��� �� deegree.org home ������ ������ ������� ����������� ������� �� ��������� ��������� ��� ���������������� ��� �������� ����������� ���  deegree.

* deegree wiki

  Available on: http://wiki.deegree.org

* deegree online demo

  Available on: http://demo.deegree.org

* deegree home

  Available on http://deegree.org/
