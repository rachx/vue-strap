<template>
    <doc-section id="tipBoxDocs" name="TipBox">
        <div class="bs-example">
            <tip-box>
                default
            </tip-box>
            <tip-box type="info">
                info
            </tip-box>
            <tip-box type="warning">
                warning
            </tip-box>
            <tip-box type="success">
                success
            </tip-box>
            <tip-box type="important">
                important
            </tip-box>
            <tip-box type="wrong">
                wrong
            </tip-box>
            <tip-box type="tip">
                tip
            </tip-box>
            <tip-box type="definition">
                definition
            </tip-box>
        </div>
        <doc-code language="markup">
            <tip-box>
                default
            </tip-box>
            <tip-box type="info">
                info
            </tip-box>
            <tip-box type="warning">
                warning
            </tip-box>
            <tip-box type="success">
                success
            </tip-box>
            <tip-box type="important">
                important
            </tip-box>
            <tip-box type="wrong">
                wrong
            </tip-box>
            <tip-box type="tip">
                tip
            </tip-box>
            <tip-box type="definition">
                definition
            </tip-box>
        </doc-code>
    </doc-section>
</template>

<script>
  import docSection from './docSection.vue'
  import docTable from './docTable.vue'
  import docCode from './docCode.vue'
  import tipBox from 'src/TipBox.vue'

  export default {
    components: {
      docSection,
      docTable,
      docCode,
      tipBox
    },
    created() {

    }
  }
</script>
