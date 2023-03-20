---
description: >-
  SeaSketch allows users to draw potential management plans and share them with
  other users.
---

# Sketching Tools

{% hint style="info" %}
This article covers:

* [Navigating to sketching tools](sketching-tools.md#navigating-to-sketching-tools)
* [Creating a new sketch](sketching-tools.md#create-a-new-sketch)
* [Sketching](sketching-tools.md#sketching)
  * [Sketching a shape](sketching-tools.md#sketching-a-shape)
  * [Automatic clipping](sketching-tools.md#automatic-clipping)
  * [Editing and deleting shapes](sketching-tools.md#editing-and-deleting-shapes)
  * [Adding a name and description](sketching-tools.md#adding-a-name-and-description)
* [Organizing Sketches](sketching-tools.md#organizing-sketches)
* [Downloading Sketches](sketching-tools.md#downloading-sketches)
{% endhint %}

## Navigating to Sketching Tools

To get started sketching, click 'Sketching Tools' or the polygon symbol <img src="../.gitbook/assets/image (11) (1).png" alt="" data-size="line"> in the main menu. If you haven't made any sketches yet, the panel that appears will be blank as shown below.

<figure><img src="../.gitbook/assets/Screenshot 2023-03-09 at 1.42.56 PM.png" alt=""><figcaption><p>Sketching Tools panel</p></figcaption></figure>

## Create a New Sketch

To create a sketch, click <img src="../.gitbook/assets/image (6).png" alt="" data-size="line"> at the top of the panel. A dropdown menu will appear containing the various "sketch classes" that pertain to your project. The exact list of classes and parameters associated with each class tend to be unique to each project. If you're not sure which sketch class to use, talk to a project administrator.

<figure><img src="../.gitbook/assets/sketching.png" alt=""><figcaption><p>Creating a new sketch</p></figcaption></figure>

## Sketching

Once you've selected the type of sketch you want to create, you'll enter the sketching interface in which you can draw your desired area on the map and give it a name and description.&#x20;

### Sketching a shape

To start sketching, move your cursor onto the map viewer and click to create the first vertex of your polygon. From here, continue clicking to create additional vertices along the perimeter of your envisioned shape. When your shape is complete you can either double-click the end point or click your starting point to finish editing.&#x20;

<figure><img src="../.gitbook/assets/drawing-shapes-2.gif" alt=""><figcaption><p>Sketching a new shape</p></figcaption></figure>

### Automatic clipping

When you finish editing a shape, you'll see its boundary briefly light up and become animated. Once this is complete, some parts of your shape might be cropped or clipped out. Most sketch classes will automatically remove certain areas whether they be land, areas extending beyond EEZ boundaries, or other areas specific to the project.

<figure><img src="../.gitbook/assets/Screenshot 2023-03-09 at 2.44.34 PM.png" alt=""><figcaption><p>In the process of clipping the newly drawn shape</p></figcaption></figure>

### Editing and deleting shapes

Once your shape has finished clipping and appears green and static, you can delete or edit it by clicking on it.

To delete your shape and start over, simply click the trashcan symbol <img src="../.gitbook/assets/image (10).png" alt="" data-size="line"> in the menu near the bottom of the screen.

To edit your shape, you can drag existing vertices to new locations, or click and drag the smaller orange points between vertices to create new ones.

Click <img src="../.gitbook/assets/image (4) (1).png" alt="" data-size="line"> at the bottom when finished.

<figure><img src="../.gitbook/assets/edit-shapes.png" alt=""><figcaption><p>Shape editing interface</p></figcaption></figure>

If a sketch has already been created, you can still edit it by clicking it on the map viewer or right clicking its name in the left panel and hitting 'Edit'.

### Adding a name and description

Adding a distinctive name and informative description is crucial for collaborative planning efforts. You can add these details within the sketching interface.

<figure><img src="../.gitbook/assets/Screenshot 2023-03-09 at 3.35.43 PM.png" alt=""><figcaption><p>Naming and describing newly created area</p></figcaption></figure>

## Organizing Sketches

If you create multiple sketches, you can group them in a couple ways. You can create and add sketches to a folder — this is purely for organizational purposes. Or, if they are part of a proposed network of managed areas, you can compile them into a network. Networks can be assessed as a collective area when generating analytics reports. [More on reports below](sketching-tools.md#generating-reports).

To create a folder or network, click <img src="../.gitbook/assets/image (11).png" alt="" data-size="line"> and select the respective option from the dropdown menu. After giving the grouping a name (and description in the case of a network), you can drag and drop individual areas to add them to the group.

<figure><img src="../.gitbook/assets/create-network-2.gif" alt=""><figcaption><p>Creating a network and adding areas to it</p></figcaption></figure>

## Downloading Sketches

You can download any shapes you create as GeoJSON files. Just right click on the area or network you want to download and hit <img src="../.gitbook/assets/image (1).png" alt="" data-size="line">. GeoJSON files can easily be loaded into a desktop GIS program like ArcMap or QGIS.&#x20;

<figure><img src="../.gitbook/assets/download-sketch.png" alt=""><figcaption><p>Downloading "MPA Network" as a GeoJSON file</p></figcaption></figure>
