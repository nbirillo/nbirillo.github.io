---
title: "Reflekt"
collection: tools
permalink: /tool/reflekt
pdf: 'https://arxiv.org/abs/2202.06033'
tool: 'https://github.com/JetBrains-Research/reflekt'
tag: 'A plugin for Kotlin compiler for compile-time reflection.'
abstract: "<p><b>Reflekt</b> is a compile-time reflection library that leverages the flows of the standard reflection approach and can find classes, objects (singleton classes) or functions by some conditions in compile-time. Instead of relying on JVM reflection, Reflekt performs compile-time resolution of reflection queries using Kotlin compiler analysis, providing a convenient reflection API without actually using reflection. Reflekt is a joint project of JetBrains Research and the Kotless team. The main reason for its creation was the necessity of GraalVM support in modern Java applications, especially on Serverless workloads. With the help of the Reflekt project, Kotless will be able to provide access to GraalVM to users of historically reflection-based frameworks such as Spring or their own Kotless DSL.</p>"
---