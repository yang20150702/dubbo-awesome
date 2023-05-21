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
# Warmup Iteration   1: 2.360 ops/ms
# Warmup Iteration   2: 5.878 ops/ms
# Warmup Iteration   3: 9.294 ops/ms
Iteration   1: 9.915 ops/ms
Iteration   2: 9.145 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.535 ±(99.9%) 7.031 ops/ms [Average]
  (min, avg, max) = (9.145, 9.535, 9.915), stdev = 0.385
  CI (99.9%): [2.504, 16.566] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 9.447 ops/ms
# Warmup Iteration   3: 10.247 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.257 ±(99.9%) 7.448 ops/ms [Average]
  (min, avg, max) = (9.786, 10.257, 10.512), stdev = 0.408
  CI (99.9%): [2.809, 17.705] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ops/ms
# Warmup Iteration   2: 8.986 ops/ms
# Warmup Iteration   3: 9.698 ops/ms
Iteration   1: 9.912 ops/ms
Iteration   2: 10.013 ops/ms
Iteration   3: 9.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.845 ±(99.9%) 3.828 ops/ms [Average]
  (min, avg, max) = (9.610, 9.845, 10.013), stdev = 0.210
  CI (99.9%): [6.017, 13.673] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.146 ops/ms
# Warmup Iteration   2: 7.732 ops/ms
# Warmup Iteration   3: 8.508 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.327 ±(99.9%) 2.938 ops/ms [Average]
  (min, avg, max) = (8.170, 8.327, 8.492), stdev = 0.161
  CI (99.9%): [5.389, 11.265] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.233 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.007 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
Iteration   3: 3.167 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.202 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.167, 3.202, 3.269), stdev = 0.058
  CI (99.9%): [2.151, 4.254] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.559 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.120 ±(99.9%) 0.834 ms/op [Average]
  (min, avg, max) = (3.094, 3.120, 3.173), stdev = 0.046
  CI (99.9%): [2.287, 3.954] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.177 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.005 ms/op
Iteration   1: 3.284 ±(99.9%) 0.004 ms/op
Iteration   2: 3.241 ±(99.9%) 0.004 ms/op
Iteration   3: 3.192 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.192, 3.239, 3.284), stdev = 0.046
  CI (99.9%): [2.401, 4.078] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.008 ms/op
Iteration   1: 3.745 ±(99.9%) 0.008 ms/op
Iteration   2: 3.683 ±(99.9%) 0.011 ms/op
Iteration   3: 3.799 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (3.683, 3.742, 3.799), stdev = 0.058
  CI (99.9%): [2.679, 4.806] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.672 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.009 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 20.938 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 20.115 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299701
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16002 
    [ 2.500,  5.000) = 279291 
    [ 5.000,  7.500) = 3390 
    [ 7.500, 10.000) = 585 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.349 ms/op
     p(99.9900) =     22.119 ms/op
     p(99.9990) =     22.971 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.013 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 20.657 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 21.293 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.918 ms/op
                 existUser·p0.9999: 20.192 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311552
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17605 
    [ 2.500,  5.000) = 290626 
    [ 5.000,  7.500) = 2770 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      9.761 ms/op
     p(99.9900) =     20.999 ms/op
     p(99.9990) =     21.980 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.314 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  17.180 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.360 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  20.697 ms/op
                 getUser·p0.9999: 25.296 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  11.130 ms/op
                 getUser·p0.9999: 22.743 ms/op
                 getUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292043
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12480 
    [ 2.500,  5.000) = 272079 
    [ 5.000,  7.500) = 6626 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     16.862 ms/op
     p(99.9900) =     24.294 ms/op
     p(99.9990) =     25.949 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.749 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.011 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  17.221 ms/op
                 listUser·p0.9999: 22.884 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 3.702 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.544 ms/op
                 listUser·p0.9999: 15.423 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   3: 3.707 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   3.936 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 13.992 ms/op
                 listUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258118
  mean =      3.718 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 252222 
    [ 5.000,  7.500) = 4293 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     21.770 ms/op
     p(99.9990) =     23.913 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.535 ± 7.031  ops/ms
ClientPb.existUser                       thrpt       3  10.257 ± 7.448  ops/ms
ClientPb.getUser                         thrpt       3   9.845 ± 3.828  ops/ms
ClientPb.listUser                        thrpt       3   8.327 ± 2.938  ops/ms
ClientPb.createUser                       avgt       3   3.202 ± 1.051   ms/op
ClientPb.existUser                        avgt       3   3.120 ± 0.834   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 0.838   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 1.064   ms/op
ClientPb.createUser                     sample  299701   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.878           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.119           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.593           ms/op
ClientPb.existUser                      sample  311552   3.079 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.761           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.086           ms/op
ClientPb.getUser                        sample  292043   3.285 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.176           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.862           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.294           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.706           ms/op
ClientPb.listUser                       sample  258118   3.718 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.586           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.770           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
