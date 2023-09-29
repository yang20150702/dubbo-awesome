# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.309 ops/ms
# Warmup Iteration   2: 5.878 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.599 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.547 ±(99.9%) 2.476 ops/ms [Average]
  (min, avg, max) = (9.393, 9.547, 9.649), stdev = 0.136
  CI (99.9%): [7.071, 12.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 10.193 ops/ms
Iteration   1: 10.079 ops/ms
Iteration   2: 10.406 ops/ms
Iteration   3: 10.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.175 ±(99.9%) 3.667 ops/ms [Average]
  (min, avg, max) = (10.040, 10.175, 10.406), stdev = 0.201
  CI (99.9%): [6.508, 13.842] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.268 ops/ms
# Warmup Iteration   2: 9.191 ops/ms
# Warmup Iteration   3: 9.617 ops/ms
Iteration   1: 9.803 ops/ms
Iteration   2: 9.931 ops/ms
Iteration   3: 9.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.884 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (9.803, 9.884, 9.931), stdev = 0.070
  CI (99.9%): [8.605, 11.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ops/ms
# Warmup Iteration   2: 7.633 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.367 ±(99.9%) 3.451 ops/ms [Average]
  (min, avg, max) = (8.221, 8.367, 8.581), stdev = 0.189
  CI (99.9%): [4.916, 11.818] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.949 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.005 ms/op
Iteration   1: 3.292 ±(99.9%) 0.007 ms/op
Iteration   2: 3.246 ±(99.9%) 0.004 ms/op
Iteration   3: 3.215 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.251 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.215, 3.251, 3.292), stdev = 0.039
  CI (99.9%): [2.547, 3.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.711 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.002 ms/op
Iteration   1: 3.133 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
Iteration   3: 3.127 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (3.127, 3.131, 3.134), stdev = 0.004
  CI (99.9%): [3.063, 3.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.586 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.002 ms/op
Iteration   1: 3.245 ±(99.9%) 0.002 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.262 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.235 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (3.198, 3.235, 3.262), stdev = 0.033
  CI (99.9%): [2.635, 3.835] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.371 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.003 ms/op
Iteration   1: 3.836 ±(99.9%) 0.005 ms/op
Iteration   2: 3.800 ±(99.9%) 0.006 ms/op
Iteration   3: 3.812 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.816 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (3.800, 3.816, 3.836), stdev = 0.019
  CI (99.9%): [3.477, 4.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.009 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.434 ms/op
                 createUser·p0.999:  13.836 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  16.937 ms/op
                 createUser·p0.9999: 22.008 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  14.616 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293421
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15667 
    [ 2.500,  5.000) = 273298 
    [ 5.000,  7.500) = 3528 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 172 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     14.699 ms/op
     p(99.9900) =     25.143 ms/op
     p(99.9990) =     26.186 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.604 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  13.915 ms/op
                 existUser·p0.9999: 18.656 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 20.446 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   3: 3.142 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 20.206 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301522
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17433 
    [ 2.500,  5.000) = 278477 
    [ 5.000,  7.500) = 4635 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.901 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.211 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
Iteration   1: 3.387 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  16.336 ms/op
                 getUser·p0.9999: 20.206 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.303 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  16.877 ms/op
                 getUser·p0.9999: 24.833 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  13.959 ms/op
                 getUser·p0.9999: 22.596 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288370
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6058 
    [ 2.500,  5.000) = 274322 
    [ 5.000,  7.500) = 6842 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     16.116 ms/op
     p(99.9900) =     22.888 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.990 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.011 ms/op
Iteration   1: 3.925 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.515 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.704 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   2: 3.910 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.539 ms/op
                 listUser·p0.9999: 15.119 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   3: 3.953 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 15.254 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244243
  mean =      3.929 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 237223 
    [ 5.000,  7.500) = 5239 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 407 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     20.171 ms/op
     p(99.9990) =     24.544 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.547 ± 2.476  ops/ms
ClientPb.existUser                       thrpt       3  10.175 ± 3.667  ops/ms
ClientPb.getUser                         thrpt       3   9.884 ± 1.279  ops/ms
ClientPb.listUser                        thrpt       3   8.367 ± 3.451  ops/ms
ClientPb.createUser                       avgt       3   3.251 ± 0.704   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 0.068   ms/op
ClientPb.getUser                          avgt       3   3.235 ± 0.600   ms/op
ClientPb.listUser                         avgt       3   3.816 ± 0.339   ms/op
ClientPb.createUser                     sample  293421   3.269 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.699           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.143           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  301522   3.183 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.693           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.901           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.988           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.201           ms/op
ClientPb.getUser                        sample  288370   3.327 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.096           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.116           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.888           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.083           ms/op
ClientPb.listUser                       sample  244243   3.929 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.795           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.171           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.395           ms/op
