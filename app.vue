
<script setup>
import { SerialPort } from 'serialport';

new SerialPort('COM1', { baudRate: 9600 });
</script>