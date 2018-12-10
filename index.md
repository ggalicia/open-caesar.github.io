Open CAESAR is a project that develops open-source components that are used within the CAESAR system. The project aims at fostering collaboration between industry and resesrch partners that are co-developing the CAESAR system.

## What is CAESAR?

CAESAR stands for Computer Aided Engineering for Systems Architectures. It is a software system that supports the transformation of Systems Engineering practices into rigorous, integrated and model-centric engineerin processes. CAESAR is used by projects developing complex systems throughout the systems development life cycle. CAESAR does not necessarily intend to replace existing Systems Engineering tools that are used by the projects. Instead, it aims at integrating them in end-to-end methdology-driven use cases. This integration focuses on the information that is produced or consumed by these tools. Since this information is heterogeneous in nature, CAESAR normalizes this information and represent it in a common (tool-neutral) format called OML 2.

## What is OML 2?

OML 2 stands for the v2 of the Ontology Modeling Language. OML 2 is the lingua franca of CAESAR that is used to represent the information. The language is inspired by and based on the W3C standard Web Ontooogy Language 2 Description Logic ([OWL 2 DL](https://www.w3.org/TR/2012/REC-owl2-syntax-20121211/)). Specifically, OML 2 provides an abstraction over a number of patterns that are expressed using a subset of OWL 2 DL plus Semantic Web Rule Language ([SWRL](https://www.w3.org/Submission/SWRL/)) rules. Those abstractions are used to represent different kinds of information related to Systems Engineering including vocabulary models, design models and analysis models.

The abstract syntax of OML 2 is defined using the Eclipse Modeling Framework ([EMF](https://www.eclipse.org/modeling/emf/)). This means the language has a Java-based Object-Oriented API for manipulating its models. The language also has a textual syntax that is defined using the [Xtext](https://www.eclipse.org/Xtext/) framework. This gives it a concise textual grammar that faciliates authoring models using a text editor. In fact, the textual syntax support is packaged as a [OML 2 Language Server](https://github.com/open-caesar/oml2-language-server) that conforms to the Language Server Protocol (LSP) standard. This server enables the OML 2 models to be edited in various IDEs including [Eclipse](https://github.com/open-caesar/oml2-eclipse), [Theia](https://github.com/open-caesar/oml2-theia) and [VS Code](https://github.com/open-caesar/oml2-vscode).