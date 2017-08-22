# Magento 2 Snippets

A nice start to a collection of Magento 2 code snippets for Visual Studio Code!

## Table of Contents
- [Layouts](#layouts)
  - [Instructions](#instructions)
    - [Scaffold](#scaffold)
    - [Block](#block)
    - [Block Wrap](#block-wrap)
    - [Container](#container)
    - [Container Wrap](#container-wrap)
    - [Reference Block](#reference-block)
    - [Reference Container](#reference-container)
    - [Move](#move)
    - [Remove](#remove)
    - [Update](#update)
    - [Arguments](#arguements)
    - [Argument](#arguement)
  - [Attributes](#attributes)
    - [Translate](#translate)
    - [xsi:type](#xsi-type)
    - [Handle](#Handle)
    - [Destination](#destination)
    - [Element](#element)
    - [htmlId](#htmlid)
    - [htmlClass](#htmlclass)
    - [htmlTag](#htmltag)
    - [Output](#output)
    - [Label](#label)
    - [As](#as)
    - [Template](#template)
    - [Class](#class)
    - [Name](#name)
    - [Before](#before)
    - [After](#after)
    - [Cacheable](#cacheable)
    - [Display](#display)
    - [Remove](#remove)

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
### xsi:type
### Handle
### Destination
### Element
### htmlId
### htmlClass
### htmlTag
### Output
### Label
### As
### Template
### Class
### Name
### Before
### After
### Cacheable
### Display
### Remove
