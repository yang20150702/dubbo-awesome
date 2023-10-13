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
# Warmup Iteration   1: 2.089 ops/ms
# Warmup Iteration   2: 5.759 ops/ms
# Warmup Iteration   3: 8.496 ops/ms
Iteration   1: 9.143 ops/ms
Iteration   2: 9.202 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.266 ±(99.9%) 3.002 ops/ms [Average]
  (min, avg, max) = (9.143, 9.266, 9.453), stdev = 0.165
  CI (99.9%): [6.264, 12.268] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.756 ops/ms
# Warmup Iteration   2: 8.895 ops/ms
# Warmup Iteration   3: 9.385 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.748 ops/ms
Iteration   3: 9.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.712 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (9.655, 9.712, 9.748), stdev = 0.050
  CI (99.9%): [8.800, 10.624] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.889 ops/ms
# Warmup Iteration   2: 8.562 ops/ms
# Warmup Iteration   3: 9.252 ops/ms
Iteration   1: 9.065 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.126 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (9.065, 9.126, 9.191), stdev = 0.063
  CI (99.9%): [7.976, 10.277] (assumes normal distribution)


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
# Warmup Iteration   1: 2.731 ops/ms
# Warmup Iteration   2: 7.103 ops/ms
# Warmup Iteration   3: 7.744 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 7.669 ops/ms
Iteration   3: 7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.705 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (7.669, 7.705, 7.748), stdev = 0.040
  CI (99.9%): [6.972, 8.438] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.130 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.005 ms/op
Iteration   1: 3.633 ±(99.9%) 0.006 ms/op
Iteration   2: 3.557 ±(99.9%) 0.003 ms/op
Iteration   3: 3.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.546 ±(99.9%) 1.711 ms/op [Average]
  (min, avg, max) = (3.447, 3.546, 3.633), stdev = 0.094
  CI (99.9%): [1.834, 5.257] (assumes normal distribution)


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
# Warmup Iteration   1: 8.303 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.002 ms/op
Iteration   1: 3.406 ±(99.9%) 0.004 ms/op
Iteration   2: 3.368 ±(99.9%) 0.006 ms/op
Iteration   3: 3.353 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.375 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.353, 3.375, 3.406), stdev = 0.027
  CI (99.9%): [2.879, 3.872] (assumes normal distribution)


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
# Warmup Iteration   1: 9.580 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.004 ms/op
Iteration   1: 3.511 ±(99.9%) 0.002 ms/op
Iteration   2: 3.520 ±(99.9%) 0.004 ms/op
Iteration   3: 3.482 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.504 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (3.482, 3.504, 3.520), stdev = 0.020
  CI (99.9%): [3.144, 3.864] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.341 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.007 ms/op
Iteration   1: 4.134 ±(99.9%) 0.007 ms/op
Iteration   2: 3.996 ±(99.9%) 0.013 ms/op
Iteration   3: 4.101 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.077 ±(99.9%) 1.312 ms/op [Average]
  (min, avg, max) = (3.996, 4.077, 4.134), stdev = 0.072
  CI (99.9%): [2.765, 5.389] (assumes normal distribution)


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
# Warmup Iteration   1: 8.866 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  21.007 ms/op
                 createUser·p0.9999: 23.541 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  23.527 ms/op
                 createUser·p0.9999: 35.501 ms/op
                 createUser·p1.00:   38.404 ms/op

Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.928 ms/op
                 createUser·p0.999:  21.365 ms/op
                 createUser·p0.9999: 26.276 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277034
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7152 
    [ 2.500,  5.000) = 263989 
    [ 5.000,  7.500) = 4780 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     21.264 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     37.481 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.011 ms/op
Iteration   1: 3.338 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  8.407 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 26.214 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  19.983 ms/op
                 existUser·p0.9999: 28.443 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285864
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7416 
    [ 2.500,  5.000) = 273256 
    [ 5.000,  7.500) = 4403 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.729 ms/op
     p(99.9000) =     14.886 ms/op
     p(99.9900) =     26.457 ms/op
     p(99.9990) =     28.648 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 9.231 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.011 ms/op
Iteration   1: 3.553 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  22.811 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  22.774 ms/op
                 getUser·p0.9999: 31.376 ms/op
                 getUser·p1.00:   33.063 ms/op

Iteration   3: 3.451 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  10.983 ms/op
                 getUser·p0.9999: 27.154 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274190
  mean =      3.499 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4226 
    [ 2.500,  5.000) = 263775 
    [ 5.000,  7.500) = 4904 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     21.391 ms/op
     p(99.9900) =     30.035 ms/op
     p(99.9990) =     32.802 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 10.517 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.013 ms/op
Iteration   1: 4.303 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  19.893 ms/op
                 listUser·p0.9999: 23.907 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 4.107 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 4.060 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230920
  mean =      4.154 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 220951 
    [ 5.000,  7.500) = 7797 
    [ 7.500, 10.000) = 1324 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.878 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.492 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.266 ± 3.002  ops/ms
ClientPb.existUser                       thrpt       3   9.712 ± 0.912  ops/ms
ClientPb.getUser                         thrpt       3   9.126 ± 1.150  ops/ms
ClientPb.listUser                        thrpt       3   7.705 ± 0.733  ops/ms
ClientPb.createUser                       avgt       3   3.546 ± 1.711   ms/op
ClientPb.existUser                        avgt       3   3.375 ± 0.496   ms/op
ClientPb.getUser                          avgt       3   3.504 ± 0.360   ms/op
ClientPb.listUser                         avgt       3   4.077 ± 1.312   ms/op
ClientPb.createUser                     sample  277034   3.463 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.152           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.341           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.404           ms/op
ClientPb.existUser                      sample  285864   3.356 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.729           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.886           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.770           ms/op
ClientPb.getUser                        sample  274190   3.499 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.391           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.035           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.063           ms/op
ClientPb.listUser                       sample  230920   4.154 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.134           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.428           ms/op
