# -*- coding: utf-8 -*-

task :default => [ :dump ]

desc 'dump hostvars'
task :dump do
  sh "ansible-playbook -i hosts test.yml"
end

# Local Variables:
# mode: Ruby
# indent-tabs-mode: nil
# End:
