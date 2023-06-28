# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.163 ops/ms
# Warmup Iteration   2: 2.443 ops/ms
# Warmup Iteration   3: 5.484 ops/ms
Iteration   1: 5.723 ops/ms
Iteration   2: 6.047 ops/ms
Iteration   3: 6.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.925 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (5.723, 5.925, 6.047), stdev = 0.176
  CI (99.9%): [2.709, 9.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 5.304 ops/ms
# Warmup Iteration   3: 6.147 ops/ms
Iteration   1: 6.209 ops/ms
Iteration   2: 6.128 ops/ms
Iteration   3: 5.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.103 ±(99.9%) 2.190 ops/ms [Average]
  (min, avg, max) = (5.973, 6.103, 6.209), stdev = 0.120
  CI (99.9%): [3.913, 8.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.563 ops/ms
# Warmup Iteration   2: 4.151 ops/ms
# Warmup Iteration   3: 5.728 ops/ms
Iteration   1: 5.986 ops/ms
Iteration   2: 5.822 ops/ms
Iteration   3: 6.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.939 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (5.822, 5.939, 6.009), stdev = 0.102
  CI (99.9%): [4.073, 7.805] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 3.752 ops/ms
# Warmup Iteration   3: 4.985 ops/ms
Iteration   1: 5.188 ops/ms
Iteration   2: 5.273 ops/ms
Iteration   3: 5.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.270 ±(99.9%) 1.459 ops/ms [Average]
  (min, avg, max) = (5.188, 5.270, 5.348), stdev = 0.080
  CI (99.9%): [3.810, 6.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.837 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 5.821 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.454 ±(99.9%) 0.019 ms/op
Iteration   1: 5.247 ±(99.9%) 0.018 ms/op
Iteration   2: 5.285 ±(99.9%) 0.020 ms/op
Iteration   3: 5.401 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.311 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (5.247, 5.311, 5.401), stdev = 0.080
  CI (99.9%): [3.849, 6.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.234 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.724 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.133 ±(99.9%) 0.014 ms/op
Iteration   1: 4.946 ±(99.9%) 0.016 ms/op
Iteration   2: 5.144 ±(99.9%) 0.013 ms/op
Iteration   3: 5.282 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.124 ±(99.9%) 3.076 ms/op [Average]
  (min, avg, max) = (4.946, 5.124, 5.282), stdev = 0.169
  CI (99.9%): [2.048, 8.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.960 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.652 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.139 ±(99.9%) 0.017 ms/op
Iteration   1: 5.222 ±(99.9%) 0.008 ms/op
Iteration   2: 5.304 ±(99.9%) 0.007 ms/op
Iteration   3: 5.152 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.226 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (5.152, 5.226, 5.304), stdev = 0.076
  CI (99.9%): [3.844, 6.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.225 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 8.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.255 ±(99.9%) 0.012 ms/op
Iteration   1: 6.191 ±(99.9%) 0.010 ms/op
Iteration   2: 6.125 ±(99.9%) 0.013 ms/op
Iteration   3: 6.268 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.195 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (6.125, 6.195, 6.268), stdev = 0.072
  CI (99.9%): [4.890, 7.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.974 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.746 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.024 ms/op
Iteration   1: 5.158 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.083 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  23.909 ms/op
                 createUser·p0.9999: 29.655 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   2: 5.186 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   9.776 ms/op
                 createUser·p0.999:  25.928 ms/op
                 createUser·p0.9999: 28.836 ms/op
                 createUser·p1.00:   30.245 ms/op

Iteration   3: 5.137 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.400 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  27.593 ms/op
                 createUser·p0.9999: 29.484 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 186084
  mean =      5.160 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 105168 
    [ 5.000,  7.500) = 73275 
    [ 7.500, 10.000) = 5806 
    [10.000, 12.500) = 1284 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 108 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     24.827 ms/op
     p(99.9900) =     29.406 ms/op
     p(99.9990) =     30.249 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.135 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.793 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.233 ±(99.9%) 0.020 ms/op
Iteration   1: 5.185 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  22.664 ms/op
                 existUser·p0.9999: 27.946 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   2: 5.115 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.087 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  13.599 ms/op
                 existUser·p0.9999: 32.096 ms/op
                 existUser·p1.00:   33.260 ms/op

Iteration   3: 5.249 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.160 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  30.019 ms/op
                 existUser·p0.9999: 35.652 ms/op
                 existUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185163
  mean =      5.182 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 95007 
    [ 5.000,  7.500) = 82524 
    [ 7.500, 10.000) = 6010 
    [10.000, 12.500) = 1059 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     18.034 ms/op
     p(99.9900) =     33.538 ms/op
     p(99.9990) =     36.394 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.791 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.168 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.569 ±(99.9%) 0.022 ms/op
Iteration   1: 5.493 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.904 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   10.534 ms/op
                 getUser·p0.999:  28.174 ms/op
                 getUser·p0.9999: 32.348 ms/op
                 getUser·p1.00:   33.423 ms/op

Iteration   2: 5.509 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.675 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   8.200 ms/op
                 getUser·p0.99:   11.193 ms/op
                 getUser·p0.999:  27.479 ms/op
                 getUser·p0.9999: 31.103 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 5.427 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   3.011 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.332 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  27.592 ms/op
                 getUser·p0.9999: 30.805 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175248
  mean =      5.476 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 66740 
    [ 5.000,  7.500) = 99363 
    [ 7.500, 10.000) = 7007 
    [10.000, 12.500) = 1232 
    [12.500, 15.000) = 412 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.675 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     27.591 ms/op
     p(99.9900) =     31.637 ms/op
     p(99.9990) =     33.251 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.026 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.057 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.476 ±(99.9%) 0.027 ms/op
Iteration   1: 6.243 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  27.263 ms/op
                 listUser·p0.9999: 30.418 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 6.252 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.138 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  28.408 ms/op
                 listUser·p0.9999: 33.581 ms/op
                 listUser·p1.00:   34.865 ms/op

Iteration   3: 6.160 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.047 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  25.111 ms/op
                 listUser·p0.9999: 29.348 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154316
  mean =      6.218 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 10725 
    [ 5.000,  7.500) = 128788 
    [ 7.500, 10.000) = 11180 
    [10.000, 12.500) = 2455 
    [12.500, 15.000) = 640 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     27.263 ms/op
     p(99.9900) =     31.841 ms/op
     p(99.9990) =     34.830 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.925 ± 3.216  ops/ms
ClientPb.existUser                       thrpt       3   6.103 ± 2.190  ops/ms
ClientPb.getUser                         thrpt       3   5.939 ± 1.866  ops/ms
ClientPb.listUser                        thrpt       3   5.270 ± 1.459  ops/ms
ClientPb.createUser                       avgt       3   5.311 ± 1.461   ms/op
ClientPb.existUser                        avgt       3   5.124 ± 3.076   ms/op
ClientPb.getUser                          avgt       3   5.226 ± 1.383   ms/op
ClientPb.listUser                         avgt       3   6.195 ± 1.305   ms/op
ClientPb.createUser                     sample  186084   5.160 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.669           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.827           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.406           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  185163   5.182 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.916           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.184           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.034           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.538           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.897           ms/op
ClientPb.getUser                        sample  175248   5.476 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.675           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.591           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.637           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.423           ms/op
ClientPb.listUser                       sample  154316   6.218 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.212           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.263           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.841           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.865           ms/op
