# DMA

## DMA的优势

DMA传输过程的初始化和启动由CPU完成，传输过程由DMA控制器来执行，无需CPU参与，从而节省CPU资源，提高利用率。

## 配置串口DMA接收

HAL_UART_Receive_DMA(UART_HandleTypeDef *huart,uint8_t *pData,uint16_t Size)

分别指向串口句柄，待接收数据，并加上个数

## DMA各参数

huart：串口句柄的地址

pData：待接收数据的首地址

size：待接收数据的个数

