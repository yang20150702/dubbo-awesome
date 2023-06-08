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
# Warmup Iteration   1: 2.331 ops/ms
# Warmup Iteration   2: 5.924 ops/ms
# Warmup Iteration   3: 8.918 ops/ms
Iteration   1: 9.734 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 9.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.640 ±(99.9%) 4.375 ops/ms [Average]
  (min, avg, max) = (9.368, 9.640, 9.819), stdev = 0.240
  CI (99.9%): [5.265, 14.015] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ops/ms
# Warmup Iteration   2: 9.401 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 9.970 ops/ms
Iteration   2: 10.241 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.117 ±(99.9%) 2.497 ops/ms [Average]
  (min, avg, max) = (9.970, 10.117, 10.241), stdev = 0.137
  CI (99.9%): [7.620, 12.614] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ops/ms
# Warmup Iteration   2: 8.889 ops/ms
# Warmup Iteration   3: 9.664 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.943 ±(99.9%) 1.456 ops/ms [Average]
  (min, avg, max) = (9.851, 9.943, 9.995), stdev = 0.080
  CI (99.9%): [8.487, 11.399] (assumes normal distribution)


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
# Warmup Iteration   1: 3.129 ops/ms
# Warmup Iteration   2: 7.112 ops/ms
# Warmup Iteration   3: 8.167 ops/ms
Iteration   1: 8.419 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.436 ±(99.9%) 0.956 ops/ms [Average]
  (min, avg, max) = (8.395, 8.436, 8.495), stdev = 0.052
  CI (99.9%): [7.480, 9.393] (assumes normal distribution)


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
# Warmup Iteration   1: 7.854 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
Iteration   1: 3.391 ±(99.9%) 0.010 ms/op
Iteration   2: 3.207 ±(99.9%) 0.007 ms/op
Iteration   3: 3.252 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.283 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (3.207, 3.283, 3.391), stdev = 0.096
  CI (99.9%): [1.533, 5.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.025 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
Iteration   1: 3.083 ±(99.9%) 0.005 ms/op
Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
Iteration   3: 3.061 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.051 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.008, 3.051, 3.083), stdev = 0.039
  CI (99.9%): [2.347, 3.755] (assumes normal distribution)


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
# Warmup Iteration   1: 8.039 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.003 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
Iteration   3: 3.238 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.291 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (3.238, 3.291, 3.342), stdev = 0.052
  CI (99.9%): [2.338, 4.244] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.807 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.008 ms/op
Iteration   1: 3.730 ±(99.9%) 0.008 ms/op
Iteration   2: 3.826 ±(99.9%) 0.004 ms/op
Iteration   3: 3.690 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.690, 3.749, 3.826), stdev = 0.070
  CI (99.9%): [2.475, 5.022] (assumes normal distribution)


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
# Warmup Iteration   1: 8.242 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
Iteration   1: 3.318 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  16.068 ms/op
                 createUser·p0.9999: 23.649 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.398 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  20.573 ms/op
                 createUser·p0.9999: 23.612 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  16.341 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289093
  mean =      3.320 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23033 
    [ 2.500,  5.000) = 259696 
    [ 5.000,  7.500) = 5296 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     16.446 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 6.836 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
Iteration   1: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  11.917 ms/op
                 existUser·p0.9999: 21.016 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  13.359 ms/op
                 existUser·p0.9999: 20.902 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304795
  mean =      3.146 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27645 
    [ 2.500,  5.000) = 273078 
    [ 5.000,  7.500) = 3382 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     22.070 ms/op
     p(99.9990) =     23.150 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 7.589 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.011 ms/op
Iteration   1: 3.321 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  17.074 ms/op
                 getUser·p0.9999: 25.287 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  21.379 ms/op
                 getUser·p0.9999: 25.420 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  8.886 ms/op
                 getUser·p0.9999: 20.252 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298655
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16116 
    [ 2.500,  5.000) = 276105 
    [ 5.000,  7.500) = 5527 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     17.881 ms/op
     p(99.9900) =     25.039 ms/op
     p(99.9990) =     27.067 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 8.890 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
Iteration   1: 3.711 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   6.621 ms/op
                 listUser·p0.999:  16.447 ms/op
                 listUser·p0.9999: 20.460 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 3.801 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.597 ms/op
                 listUser·p0.9999: 21.384 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 3.803 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.164 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 16.751 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254359
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 247906 
    [ 5.000,  7.500) = 4478 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     20.662 ms/op
     p(99.9990) =     21.705 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.640 ± 4.375  ops/ms
ClientPb.existUser                       thrpt       3  10.117 ± 2.497  ops/ms
ClientPb.getUser                         thrpt       3   9.943 ± 1.456  ops/ms
ClientPb.listUser                        thrpt       3   8.436 ± 0.956  ops/ms
ClientPb.createUser                       avgt       3   3.283 ± 1.750   ms/op
ClientPb.existUser                        avgt       3   3.051 ± 0.704   ms/op
ClientPb.getUser                          avgt       3   3.291 ± 0.953   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 1.274   ms/op
ClientPb.createUser                     sample  289093   3.320 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.446           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.560           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.084           ms/op
ClientPb.existUser                      sample  304795   3.146 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.161           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.626           ms/op
ClientPb.getUser                        sample  298655   3.212 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.881           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.039           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  254359   3.771 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.662           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.955           ms/op
