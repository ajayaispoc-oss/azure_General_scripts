@{concat('uploads/', formatDateTime(utcNow(), 'yyyy-MM-dd_HH-mm-ss'), '/', triggerBody()?['filename'])}
