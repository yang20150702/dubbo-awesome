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
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 5.272 ops/ms
# Warmup Iteration   3: 8.497 ops/ms
Iteration   1: 8.918 ops/ms
Iteration   2: 9.036 ops/ms
Iteration   3: 9.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.083 ±(99.9%) 3.503 ops/ms [Average]
  (min, avg, max) = (8.918, 9.083, 9.294), stdev = 0.192
  CI (99.9%): [5.580, 12.586] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.594 ops/ms
# Warmup Iteration   2: 7.913 ops/ms
# Warmup Iteration   3: 9.332 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.645 ops/ms
Iteration   3: 9.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.494 ±(99.9%) 2.392 ops/ms [Average]
  (min, avg, max) = (9.416, 9.494, 9.645), stdev = 0.131
  CI (99.9%): [7.101, 11.886] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.965 ops/ms
# Warmup Iteration   2: 8.183 ops/ms
# Warmup Iteration   3: 9.105 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.128 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.198 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (9.128, 9.198, 9.240), stdev = 0.061
  CI (99.9%): [8.086, 10.310] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 7.169 ops/ms
# Warmup Iteration   3: 7.577 ops/ms
Iteration   1: 7.533 ops/ms
Iteration   2: 7.662 ops/ms
Iteration   3: 7.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.623 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (7.533, 7.623, 7.675), stdev = 0.078
  CI (99.9%): [6.191, 9.055] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.008 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.004 ms/op
Iteration   1: 3.557 ±(99.9%) 0.004 ms/op
Iteration   2: 3.499 ±(99.9%) 0.004 ms/op
Iteration   3: 3.465 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.507 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.465, 3.507, 3.557), stdev = 0.047
  CI (99.9%): [2.654, 4.360] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.599 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.003 ms/op
Iteration   1: 3.347 ±(99.9%) 0.004 ms/op
Iteration   2: 3.313 ±(99.9%) 0.007 ms/op
Iteration   3: 3.423 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.361 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.313, 3.361, 3.423), stdev = 0.056
  CI (99.9%): [2.335, 4.388] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.025 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.006 ms/op
Iteration   1: 3.462 ±(99.9%) 0.003 ms/op
Iteration   2: 3.509 ±(99.9%) 0.004 ms/op
Iteration   3: 3.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.487 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (3.462, 3.487, 3.509), stdev = 0.024
  CI (99.9%): [3.056, 3.917] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.151 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.006 ms/op
Iteration   1: 4.226 ±(99.9%) 0.009 ms/op
Iteration   2: 4.085 ±(99.9%) 0.007 ms/op
Iteration   3: 4.178 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.163 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (4.085, 4.163, 4.226), stdev = 0.072
  CI (99.9%): [2.858, 5.468] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.132 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.014 ms/op
Iteration   1: 3.567 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.391 ms/op
                 createUser·p0.999:  20.546 ms/op
                 createUser·p0.9999: 23.270 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.568 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  21.804 ms/op
                 createUser·p0.9999: 25.364 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.418 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  18.195 ms/op
                 createUser·p0.9999: 27.021 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270111
  mean =      3.553 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5084 
    [ 2.500,  5.000) = 259449 
    [ 5.000,  7.500) = 4554 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     19.078 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     28.033 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.952 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  20.742 ms/op
                 existUser·p0.9999: 23.138 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.429 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  21.586 ms/op
                 existUser·p0.9999: 24.303 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  10.238 ms/op
                 existUser·p0.9999: 26.627 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280115
  mean =      3.428 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3792 
    [ 2.500,  5.000) = 271052 
    [ 5.000,  7.500) = 4496 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     13.296 ms/op
     p(99.9900) =     25.722 ms/op
     p(99.9990) =     27.663 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 10.550 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.012 ms/op
Iteration   1: 3.612 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.441 ms/op
                 getUser·p0.999:  20.213 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.588 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  21.282 ms/op
                 getUser·p0.9999: 24.350 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  18.851 ms/op
                 getUser·p0.9999: 26.278 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267995
  mean =      3.580 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2816 
    [ 2.500,  5.000) = 259092 
    [ 5.000,  7.500) = 4748 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     24.825 ms/op
     p(99.9990) =     26.878 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 12.204 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.771 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.014 ms/op
Iteration   1: 4.220 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.128 ms/op
                 listUser·p0.999:  20.461 ms/op
                 listUser·p0.9999: 23.465 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 4.160 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.912 ms/op
                 listUser·p0.9999: 18.174 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 4.161 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 18.895 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229511
  mean =      4.180 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 220393 
    [ 5.000,  7.500) = 7067 
    [ 7.500, 10.000) = 1081 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.200 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     21.997 ms/op
     p(99.9990) =     25.973 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.083 ± 3.503  ops/ms
ClientPb.existUser                       thrpt       3   9.494 ± 2.392  ops/ms
ClientPb.getUser                         thrpt       3   9.198 ± 1.112  ops/ms
ClientPb.listUser                        thrpt       3   7.623 ± 1.432  ops/ms
ClientPb.createUser                       avgt       3   3.507 ± 0.853   ms/op
ClientPb.existUser                        avgt       3   3.361 ± 1.026   ms/op
ClientPb.getUser                          avgt       3   3.487 ± 0.430   ms/op
ClientPb.listUser                         avgt       3   4.163 ± 1.305   ms/op
ClientPb.createUser                     sample  270111   3.553 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.418           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.078           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.788           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  280115   3.428 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.820           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.296           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.213           ms/op
ClientPb.getUser                        sample  267995   3.580 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.413           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.890           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.825           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.296           ms/op
ClientPb.listUser                       sample  229511   4.180 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.200           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.679           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.997           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.001           ms/op
