@{parameters('op_blob_loc')}/@{formatDateTime(utcNow(), 'yyyy-MM-dd_HH-mm-ss')}/@{triggerOutputs()?['headers']['x-ms-file-name-with-extension']}
