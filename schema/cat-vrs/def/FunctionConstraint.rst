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
      - A categorical label of the function change that members of this categorical variant satisfies, using ontology terms from `The Sequence Ontology <http://www.sequenceontology.org>`_. MUST be `"SO:0002052" <http://www.sequenceontology.org/browser/current_release/term/SO:0002052>`_, `"SO:0002054" <http://www.sequenceontology.org/browser/current_release/term/SO:0002054>`_, `"SO:0001561" <http://www.sequenceontology.org/browser/current_release/term/SO:0001561>`_, `"SO:0002219" <http://www.sequenceontology.org/browser/current_release/term/SO:0002219>`_, `"SO:0001557" <http://www.sequenceontology.org/browser/current_release/term/SO:0001557>`_, or `"SO:0002053" <http://www.sequenceontology.org/browser/current_release/term/SO:0002053>`_.

   *  - description
      - 
      - string
      - 0..1
      - A free-text description of the function change.
