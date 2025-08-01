# func-imxrt-flexspi-dual-ports-flash-psram
在 RT1010/1020/1050/600 上验证单 FlexSPI 同时挂 Flash 和 PSRAM 方案

<table><tbody>
    <tr>
        <th rowspan="1">Feature</th>
        <th>RT1010</th>
        <th>RT1015</th>
        <th>RT1020</th>
        <th>RT1024</th>
        <th>RT1050</th>
        <th>RT600</th>
    </tr>
    <tr>
        <td>Core/Speed</td>
        <td colspan="4">Arm CM7@500MHz</td>
        <td>Arm CM7@600MHz</td>
        <td>Arm CM33@300MHz</td>
    </tr>
    <tr>
        <td>Cache</td>
        <td>16KB-I, 8KB-D</td>
        <td colspan="3">16KB-I, 16KB-D</td>
        <td>32KB-I, 32KB-D</td>
        <td>32KB (FlexSPI)</td>
    </tr>
    <tr>
        <td>SRAM</td>
        <td colspan="2">Up to 128KB TCM</td>
        <td colspan="2">Up to 256KB TCM</td>
        <td>Up to 512KB TCM</td>
        <td>4.5MB</td>
    </tr>
    <tr>
        <td>SIP Flash</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>4MB</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td >FlexSPI</td>
        <td colspan="36">1 x Dual-channel/8-bit</td>
    </tr>
</table>


