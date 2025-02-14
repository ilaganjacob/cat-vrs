.. warning:: This data class is at a **draft** maturity level and may \
    change significantly in future releases. Maturity \
    levels are described in the :ref:`maturity-model`.

**Computational Definition**

A relative assessment in the change of protein function that members of this categorical variant satisfies.

**Information Model**

Some FunctionConstraint attributes are inherited from :ref:`Constraint`.

.. list-table::
   :class: clean-wrap
   :header-rows: 1
   :align: left
   :widths: auto

   *  - Field
      - Flags
      - Type
      - Limits
      - Description
   *  - type
      -
      - string
      - 1..1
      - MUST be "FunctionConstraint"
   *  - functionConsequence
      -
      - string
      - 1..1
      - A categorical label of the function change that members of this categorical variant satisfies, using ontology terms from [The Sequence Ontology](http://www.sequenceontology.org).
``SO:0002052`` refers to a [dominant negative variant] (http://www.sequenceontology.org/browser/current_release/term/SO:0002052), a variant where the mutated gene product adversely affects the other (wild type) gene product.
``SO:0002054`` refers to a [loss of function variant] (http://www.sequenceontology.org/browser/current_release/term/SO:0002054), a sequence variant whereby the gene product has diminished or abolished function.
``SO:0001561`` refers to a [polypeptide partial loss of function] (http://www.sequenceontology.org/browser/current_release/term/SO:0001561), a sequence variant that causes some but not all loss of polypeptide function with respect to a reference sequence.
``SO:0002219`` refers to a [functionally normal] (http://www.sequenceontology.org/browser/current_release/term/SO:0002219) variant, a sequence variant in which the function of a gene product is retained with respect to a reference.
``SO:0001557`` refers to a [polypeptide gain of function variant] (http://www.sequenceontology.org/browser/current_release/term/SO:0001557), a sequence variant which causes gain of polypeptide function with respect to a reference sequence.
``SO:0002053`` refers to a [gain of function variant] (http://www.sequenceontology.org/browser/current_release/term/SO:0002053), a sequence variant whereby new or enhanced function is conferred on the gene product.
   *  - description
      -
      - string
      - 0..1
      - A free-text description of the function change.
