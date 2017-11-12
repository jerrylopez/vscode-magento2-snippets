# Magento 2 Snippets

A nice start to a collection of Magento 2 code snippets for Visual Studio Code!

## Table of Contents

### Layouts
<details>
  <summary><a href="#instructions">Instructions</a></summary>
  <ul>
    <li><a href="#scaffold">Scaffold</a></li>
    <li><a href="#block">Block</a></li>
    <li><a href="#block-wrap">Block Wrap</a></li>
    <li><a href="#container">Container</a></li>
    <li><a href="#container-wrap">Container Wrap</a></li>
    <li><a href="#reference-block">Reference Block</a></li>
    <li><a href="#reference-container">Reference Container</a></li>
    <li><a href="#move">Move</a></li>
    <li><a href="#remove">Remove</a></li>
    <li><a href="#update">Update</a></li>
    <li><a href="#arguments">Arguments</a></li>
    <li><a href="#argument">Argument</a></li>
  </ul>
</details>
<details>
  <summary><a href="#attributes">Attributes</a></summary>
  <ul>
    <li><a href="#translate">Translate</a></li>
    <li><a href="#xsitype">xsi:type</a></li>
    <li><a href="#handle">Handle</a></li>
    <li><a href="#destination">Destination</a></li>
    <li><a href="#element">Element</a></li>
    <li><a href="#htmlid">htmlId</a></li>
    <li><a href="#htmlclass">htmlClass</a></li>
    <li><a href="#htmltag">htmlTag</a></li>
    <li><a href="#output">Output</a></li>
    <li><a href="#label">Label</a></li>
    <li><a href="#as">As</a></li>
    <li><a href="#template">Template</a></li>
    <li><a href="#class">Class</a></li>
    <li><a href="#name">Name</a></li>
    <li><a href="#before">Before</a></li>
    <li><a href="#after">After</a></li>
    <li><a href="#cacheable">Cacheable</a></li>
    <li><a href="#display">Display</a></li>
    <li><a href="#remove">Remove</a></li>
  </ul>
</details>

### Modules
<details>
  <summary><a href="#mod-instructions">Instructions</a></summary>
  <ul>
    <li><a href="#module-xml">Module XML</a></li>
    <li><a href="#registration-php">Registration</a></li>
  </ul>
</details>

### DI
<details>
  <summary><a href="#di-instructions">Instructions</a></summary>
  <ul>
    <li><a href="#di-scaffold">Scaffold</a></li>
    <li><a href="#preference">Preference</a></li>
    <li><a href="#type">Type</a></li>
    <li><a href="#plugin">Plugin</a></li>
    <li><a href="#virtual-type">Virtual Type</a></li>
  </ul>
</details>

### Events
<details>
  <summary><a href="#events-instructions">Instructions</a></summary>
  <ul>
    <li><a href="#events-scaffold">Scaffold</a></li>
    <li><a href="#event">Event</a></li>
    <li><a href="#observer">Observer</a></li>
  </ul>
</details>

### Routes
<details>
  <summary><a href="#routes-instructions">Instructions</a></summary>
  <ul>
    <li><a href="#routes-scaffold">Scaffold</a></li>
    <li><a href="#routers">Routers</a></li>
    <li><a href="#route">Route</a></li>
  </ul>
</details>


# Layouts

## Instructions

### Scaffold

**Trigger:** `m2.layout`

**Output:**
```xml
<?xml version="1.0"?>
<page xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="urn:magento:framework:View/Layout/etc/page_configuration.xsd">
    <body>
        
    </body>
</page>
```

### Block

**Trigger:** `m2.layout.block`

**Output:**
```xml
<block class="" name="" as="" template="" />
```

### Block Wrap

**Trigger:** `m2.layout.blockWrap`

**Output:**
```xml
<block class="" name="" as="" template="" />
    
</block>
```

### Container
**Trigger:** `m2.layout.container`

**Output:**
```xml
<container name="" label="" output="0" htmlTag="" htmlId="" htmlClass="" />
```

### Container Wrap

**Trigger:** `m2.layout.containerWrap`

**Output:**
```xml
<container name="" label="" output="0" htmlTag="" htmlId="" htmlClass="">
    
</container>
```

### Reference Block

**Trigger:** `m2.layout.refBlock`

**Output:**
```xml
<referenceBlock name="">
    
</referenceBlock>
```

### Reference Container

**Trigger:** `m2.layout.refContainer`

**Output:**
```xml
<referenceContainer name="">
    
</referenceContainer>
```

### Move

**Trigger:** `m2.layout.move`

**Output:**
```xml
<move element="" destination="" />
```

### Remove

**Trigger:** `m2.layout.remove`

**Output:**
```xml
<remove src="" />
```

### Update

**Trigger:** `m2.layout.update`

**Output:**
```xml
<update handle=""/>
```

### Arguments

**Trigger:** `m2.layout.args`

**Output:**
```xml
<arguments>
    
</arguments>
```

### Argument

**Trigger:** `m2.layout.argument`

**Output:**
```xml
<argument name="" xsi:type=""></argument>
```

## Attributes

### Translate

**Trigger:** `m2.layout.attr.translate`

**Output:**
```xml
translate=""
```

### xsi:type

**Trigger:** `m2.layout.attr.xsi:type`

**Output:**
```xml
xsi:type=""
```

### Handle

**Trigger:** `m2.layout.attr.handle`

**Output:**
```xml
handle=""
```

### Destination

**Trigger:** `m2.layout.attr.destination`

**Output:**
```xml
destination=""
```

### Element

**Trigger:** `m2.layout.attr.element`

**Output:**
```xml
element=""
```

### htmlId

**Trigger:** `m2.layout.attr.htmlId`

**Output:**
```xml
htmlId=""
```

### htmlClass

**Trigger:** `m2.layout.attr.htmlClass`

**Output:**
```xml
htmlClass=""
```

### htmlTag

**Trigger:** `m2.layout.attr.htmlTag`

**Output:**
```xml
htmlTag=""
```

### Output

**Trigger:** `m2.layout.attr.output`

**Output:**
```xml
output=""
```

### Label

**Trigger:** `m2.layout.attr.label`

**Output:**
```xml
label=""
```

### As

**Trigger:** `m2.layout.attr.as`

**Output:**
```xml
as=""
```

### Template

**Trigger:** `m2.layout.attr.template`

**Output:**
```xml
template=""
```

### Class

**Trigger:** `m2.layout.attr.class`

**Output:**
```xml
class=""
```

### Name

**Trigger:** `m2.layout.attr.name`

**Output:**
```xml
name=""
```

### Before

**Trigger:** `m2.layout.attr.before`

**Output:**
```xml
before=""
```

### After

**Trigger:** `m2.layout.attr.after`

**Output:**
```xml
after=""
```

### Cacheable

**Trigger:** `m2.layout.attr.cacheable`

**Output:**
```xml
cacheable=""
```

### Display

**Trigger:** `m2.layout.attr.display`

**Output:**
```xml
display=""
```

### Remove

**Trigger:** `m2.layout.attr.remove`

**Output:**
```xml
remove=""
```


# Modules

## Module Instructions

### Module XML

**Trigger:** `m2.module`

**Output:**
```xml
<?xml version="1.0"?>
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
        xsi:noNamespaceSchemaLocation="urn:magento:framework:ObjectManager/etc/module.xsd">
    <module name="" setup_version="0.1.0" />

</config>
```

### Registration

**Trigger:** `m2.module.registration`

**Output:**
```php
\Magento\Framework\Component\ComponentRegistrar::register(
    \Magento\Framework\Component\ComponentRegistrar::MODULE,
    '',
    __DIR__
);
```


# DI

## DI Instructions

### DI Scaffold

**Trigger:** `m2.di`

**Output:**
```xml
<?xml version="1.0"?>
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
        xsi:noNamespaceSchemaLocation="urn:magento:framework:ObjectManager/etc/config.xsd">
    
</config>
```

### Preference

**Trigger:** `m2.di.pref`

**Output:**
```xml
<preference for="" type="" />
```

### Type

**Trigger:** `m2.di.type`

**Output:**
```xml
<type name="">

</type>
```

#### Type Arguments

**Trigger:** `m2.di.type.args`

**Output:**
```xml
<arguments>
    <argument name="" xsi:type=""></argument>
</arguments>
```

#### Type Arguments Item

**Trigger:** `m2.di.type.args.item`

**Output:**
```xml
<item name="" xsi:type=""></item>
```

### Plugin

**Trigger:** `m2.di.plugin`

**Output:**
```xml
<plugin name="" 
        type=""
        sortOrder=""/>
```

### Virtual Type

**Trigger:** `m2.di.virtualtype`

**Output:**
```xml
<virtualType name="" type="">

</virtualType>
```


# Events

## Events Instructions

### Events Scaffold

**Trigger:** `m2.events`

**Output:**
```xml
<?xml version="1.0"?>
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="urn:magento:framework:Event/etc/events.xsd">

</config>
```


### Event

**Trigger:** `m2.events.event`

**Output:**
```xml
<event name="">

</event>
```


### Observer

**Trigger:** `m2.events.observer`

**Output:**
```xml
<observer name="" instance="" />
```


# Routes

## Routes Instructions

### Routes Scaffold

**Trigger:** `m2.routes`

**Output:**
```xml
<?xml version="1.0"?>
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
        xsi:noNamespaceSchemaLocation="urn:magento:framework:App/etc/routes.xsd">

</config>
```


### Routers

**Trigger:** `m2.routes.router`

**Output:**
```xml
<router id="">
    
</router>
```


### Route

**Trigger:** `m2.routes.route`

**Output:**
```xml
<route id="" frontName="">
    <module name="" />
</route>
```



