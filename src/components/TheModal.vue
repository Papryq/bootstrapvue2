<template>
        <div class="modal fade" id="enroll" tabindex="-1" aria-labelledby="enrollLabel" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="enrollLabel">Register</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
               </div>
            <div class="modal-body">
                <ModalForm />
                </div>
                <ModalButton />
        </div>
      </div>
    </div>

</template>

<script>
import ModalForm from '@/components/ModalForm.vue'
import ModalButton from '@/components/ModalButton.vue'


export default {
    name: 'TheModal',
    components: {
        ModalForm,
        ModalButton,
    },
}
</script>