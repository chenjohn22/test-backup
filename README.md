* 安裝backup
1. sudo apt-get install libz-dev
2. sudo gem install specific_install
3. sudo gem specific_install -l https://github.com/chenjohn22/test-backup.git

* backup init
1. backup generate:model --trigger my_backup \
          --archives --storages='local' --compressor='gzip'
2. vim ~/Backup/models/my_backup.rb
