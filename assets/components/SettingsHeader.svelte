<script>
import Icon from '../components/Icon.svelte';
import {l} from '../store/I18N';

export let conversation = {};

</script>

<a href="#activeMenu:" class="sidebar__header for-settings">
  <h2>{$l(conversation.conversation_id ? 'Conversation' : 'Connection')}</h2>
  <Icon name="times-circle"/>
</a>
