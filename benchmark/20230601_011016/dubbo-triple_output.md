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
# Warmup Iteration   1: 2.653 ops/ms
# Warmup Iteration   2: 6.292 ops/ms
# Warmup Iteration   3: 9.472 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 9.839 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.666 ±(99.9%) 4.560 ops/ms [Average]
  (min, avg, max) = (9.380, 9.666, 9.839), stdev = 0.250
  CI (99.9%): [5.106, 14.226] (assumes normal distribution)


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
# Warmup Iteration   1: 3.591 ops/ms
# Warmup Iteration   2: 8.830 ops/ms
# Warmup Iteration   3: 9.779 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.419 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (10.372, 10.419, 10.497), stdev = 0.069
  CI (99.9%): [9.168, 11.670] (assumes normal distribution)


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
# Warmup Iteration   1: 3.313 ops/ms
# Warmup Iteration   2: 9.322 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 9.854 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.913 ±(99.9%) 2.431 ops/ms [Average]
  (min, avg, max) = (9.819, 9.913, 10.065), stdev = 0.133
  CI (99.9%): [7.482, 12.344] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 6.959 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 8.497 ops/ms
Iteration   2: 8.320 ops/ms
Iteration   3: 8.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.408 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (8.320, 8.408, 8.497), stdev = 0.089
  CI (99.9%): [6.789, 10.028] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.354 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.003 ms/op
Iteration   1: 3.278 ±(99.9%) 0.010 ms/op
Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
Iteration   3: 3.328 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.294 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.276, 3.294, 3.328), stdev = 0.029
  CI (99.9%): [2.756, 3.831] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.817 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.004 ms/op
Iteration   1: 3.075 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.005 ms/op
Iteration   3: 3.109 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.084 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (3.068, 3.084, 3.109), stdev = 0.022
  CI (99.9%): [2.684, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 6.966 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.003 ms/op
Iteration   1: 3.175 ±(99.9%) 0.001 ms/op
Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
Iteration   3: 3.297 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.175, 3.227, 3.297), stdev = 0.063
  CI (99.9%): [2.080, 4.373] (assumes normal distribution)


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
# Warmup Iteration   1: 8.741 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.005 ms/op
Iteration   1: 3.825 ±(99.9%) 0.005 ms/op
Iteration   2: 3.849 ±(99.9%) 0.005 ms/op
Iteration   3: 3.745 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.806 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (3.745, 3.806, 3.849), stdev = 0.054
  CI (99.9%): [2.813, 4.799] (assumes normal distribution)


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
# Warmup Iteration   1: 8.461 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.011 ms/op
Iteration   1: 3.226 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  10.107 ms/op
                 createUser·p0.9999: 26.427 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  9.462 ms/op
                 createUser·p0.9999: 22.744 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.058 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  16.149 ms/op
                 createUser·p0.9999: 20.135 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293939
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18018 
    [ 2.500,  5.000) = 269437 
    [ 5.000,  7.500) = 5600 
    [ 7.500, 10.000) = 502 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     15.582 ms/op
     p(99.9900) =     25.402 ms/op
     p(99.9990) =     28.094 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.538 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.062 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.463 ms/op
                 existUser·p0.9999: 21.256 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302522
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21104 
    [ 2.500,  5.000) = 276318 
    [ 5.000,  7.500) = 4369 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     11.228 ms/op
     p(99.9900) =     22.274 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 7.347 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.010 ms/op
Iteration   1: 3.258 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  20.185 ms/op
                 getUser·p0.9999: 24.319 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  11.213 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  14.704 ms/op
                 getUser·p0.9999: 19.306 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291796
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13742 
    [ 2.500,  5.000) = 270919 
    [ 5.000,  7.500) = 6242 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     24.237 ms/op
     p(99.9990) =     25.676 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 8.234 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.012 ms/op
Iteration   1: 3.803 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 29.563 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   2: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  11.860 ms/op
                 listUser·p0.9999: 15.812 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.649 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 23.417 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254159
  mean =      3.776 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 246760 
    [ 5.000,  7.500) = 5114 
    [ 7.500, 10.000) = 1521 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 349 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.155 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     28.243 ms/op
     p(99.9990) =     30.108 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.666 ± 4.560  ops/ms
ClientPb.existUser                       thrpt       3  10.419 ± 1.251  ops/ms
ClientPb.getUser                         thrpt       3   9.913 ± 2.431  ops/ms
ClientPb.listUser                        thrpt       3   8.408 ± 1.620  ops/ms
ClientPb.createUser                       avgt       3   3.294 ± 0.537   ms/op
ClientPb.existUser                        avgt       3   3.084 ± 0.400   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 1.147   ms/op
ClientPb.listUser                         avgt       3   3.806 ± 0.993   ms/op
ClientPb.createUser                     sample  293939   3.266 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.010           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.582           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.312           ms/op
ClientPb.existUser                      sample  302522   3.171 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.639           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.228           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.274           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.314           ms/op
ClientPb.getUser                        sample  291796   3.287 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.049           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.237           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.313           ms/op
ClientPb.listUser                       sample  254159   3.776 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.346           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.155           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.243           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.900           ms/op
