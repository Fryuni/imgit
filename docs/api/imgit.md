<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [imgit](./imgit.md)

## imgit package

## Functions

|  Function | Description |
|  --- | --- |
|  [boot(prefs, platform)](./imgit.boot.md) | Initializes build context with specified options. |
|  [build\_2(asset, merges)](./imgit.build_2.md) | Default HTML builder for supported asset types (images and video). |
|  [buildAll(assets)](./imgit.buildall.md) | Builds HTML for the optimized assets to overwrite source syntax. |
|  [buildContentSource(path)](./imgit.buildcontentsource.md) | Builds serve url for content file with specified full path based on configured root option. |
|  [capture\_2(content, assets)](./imgit.capture_2.md) | Used regexp defined in options to capture the assets syntax. |
|  [captureAll(content, id)](./imgit.captureall.md) | Finds assets to transform in the document with specified content. |
|  [encodeAll(assets)](./imgit.encodeall.md) | Generates optimized versions of the source content files. |
|  [encodeAsset(asset)](./imgit.encodeasset.md) | Encodes asset content with ffmpeg. |
|  [exit()](./imgit.exit.md) | Resets build context and caches results. |
|  [fetch\_3(asset)](./imgit.fetch_3.md) | Fetches asset's source content. |
|  [fetchAll(assets)](./imgit.fetchall.md) | Downloads source content files for the resolved assets. |
|  [probe\_2(asset)](./imgit.probe_2.md) | Probes asset content with ffprobe. |
|  [probeAll(assets)](./imgit.probeall.md) | Probes downloaded asset files to identify their content properties. |
|  [resolve\_2(asset)](./imgit.resolve_2.md) | Resolves asset types supported by default. |
|  [resolveAll(assets)](./imgit.resolveall.md) | Resolves content locations and specs of the captured syntax. |
|  [resolveSpec(query)](./imgit.resolvespec.md) | Resolves spec formatted as URL query parameters. |
|  [rewrite\_2(content, assets)](./imgit.rewrite_2.md) | Default rewrite procedure. |
|  [rewriteAll(content, assets, id)](./imgit.rewriteall.md) | Rewrites content of the document with specified assets; returns modified document content. |
|  [transform(content, id)](./imgit.transform.md) | Transforms source document (eg, <code>.md</code>, <code>.jsx</code> or <code>.html</code>) with specified content replacing configured asset syntax with optimized HTML. |

## Namespaces

|  Namespace | Description |
|  --- | --- |
|  [build](./imgit.build.md) |  |
|  [capture](./imgit.capture.md) |  |
|  [encode](./imgit.encode.md) |  |
|  [fetch\_2](./imgit.fetch_2.md) |  |
|  [probe](./imgit.probe.md) |  |
|  [resolve](./imgit.resolve.md) |  |
|  [rewrite](./imgit.rewrite.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [cache](./imgit.cache.md) | Cached results of the build operations. |
|  [cfg](./imgit.cfg.md) | Current build configuration. |
|  [CONTAINER\_ATTR](./imgit.container_attr.md) | Attribute expected on containers of HTML generated for imgit content. |
|  [COVER\_CONTAINED\_STYLE](./imgit.cover_contained_style.md) | CSS style applied to contained elements, siblings to cover element. |
|  [COVER\_CONTAINER\_STYLE](./imgit.cover_container_style.md) | CSS style applied to container of cover element. |
|  [COVER\_STYLE](./imgit.cover_style.md) | CSS style applied to cover element itself. |
|  [ctx](./imgit.ctx.md) | Shared mutable state of the current build operation. |
|  [defaults](./imgit.defaults.md) | Default build server configuration. |
|  [LOADABLE\_ATTR](./imgit.loadable_attr.md) | Attribute expected on HTML elements loaded by imgit. |
|  [stages](./imgit.stages.md) | Individual document transformation stages. |
|  [std](./imgit.std.md) | Platform-specific APIs. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [AssetSpec](./imgit.assetspec.md) | Per-asset specifications assigned by the user. |
|  [AssetSyntax](./imgit.assetsyntax.md) | Asset syntax captured from transformed document. |
|  [BuiltAsset](./imgit.builtasset.md) | Final product of asset transformation with associated HTML. |
|  [Cache\_2](./imgit.cache_2.md) | Cached results of the build operations. Each property is persisted as a standalone JSON file between build runs. Custom properties can be added. |
|  [CacheOptions](./imgit.cacheoptions.md) | Configures server cache. |
|  [CapturedAsset](./imgit.capturedasset.md) | Asset captured from transformed document. |
|  [ContentInfo](./imgit.contentinfo.md) | Result of probing a content file. |
|  [EncodedAsset](./imgit.encodedasset.md) | Asset with all the applicable encoded/generated content available on local file system. |
|  [EncodedContent](./imgit.encodedcontent.md) | Optimized source of an asset with optional generated content. |
|  [EncodeOptions](./imgit.encodeoptions.md) | Configures assets encoding. |
|  [EncodeSpec](./imgit.encodespec.md) | Configures transformation to use when encoding. |
|  [EncodeSpecMap](./imgit.encodespecmap.md) | Encode parameters mapped by source content MIME type or regex of the type. |
|  [FetchedAsset](./imgit.fetchedasset.md) | Asset with all the applicable source content files available on the local file system. |
|  [FetchedContent](./imgit.fetchedcontent.md) | Fetched source content of an asset. |
|  [FetchOptions](./imgit.fetchoptions.md) | Configures remote assets downloading behaviour. |
|  [Options](./imgit.options.md) | Configures server behaviour. |
|  [Platform](./imgit.platform.md) | Platform-specific APIs used in build operations. |
|  [Plugin\_2](./imgit.plugin_2.md) | External imgit extension. |
|  [PluginInjection](./imgit.plugininjection.md) | Used to inject client-side content for a plugin. |
|  [Prefs](./imgit.prefs.md) | User-defined build preferences. |
|  [ProbedAsset](./imgit.probedasset.md) | Asset with identified source content. |
|  [ProbedContent](./imgit.probedcontent.md) | Identified source content of an asset. |
|  [ResolvedAsset](./imgit.resolvedasset.md) | Asset with resolved source content locations and specs. |
|  [ResolvedContent](./imgit.resolvedcontent.md) | Source content of an asset resolved from captured syntax. |

