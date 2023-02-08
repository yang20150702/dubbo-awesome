# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 5.765 ops/ms
# Warmup Iteration   3: 8.582 ops/ms
Iteration   1: 9.097 ops/ms
Iteration   2: 9.428 ops/ms
Iteration   3: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.250 ±(99.9%) 3.045 ops/ms [Average]
  (min, avg, max) = (9.097, 9.250, 9.428), stdev = 0.167
  CI (99.9%): [6.204, 12.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.008 ops/ms
# Warmup Iteration   2: 8.381 ops/ms
# Warmup Iteration   3: 9.590 ops/ms
Iteration   1: 9.667 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 9.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.737 ±(99.9%) 2.067 ops/ms [Average]
  (min, avg, max) = (9.667, 9.737, 9.868), stdev = 0.113
  CI (99.9%): [7.670, 11.804] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 8.494 ops/ms
# Warmup Iteration   3: 9.180 ops/ms
Iteration   1: 8.836 ops/ms
Iteration   2: 9.436 ops/ms
Iteration   3: 9.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.194 ±(99.9%) 5.780 ops/ms [Average]
  (min, avg, max) = (8.836, 9.194, 9.436), stdev = 0.317
  CI (99.9%): [3.415, 14.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.679 ops/ms
# Warmup Iteration   2: 7.354 ops/ms
# Warmup Iteration   3: 7.748 ops/ms
Iteration   1: 7.812 ops/ms
Iteration   2: 7.965 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.940 ±(99.9%) 2.162 ops/ms [Average]
  (min, avg, max) = (7.812, 7.940, 8.045), stdev = 0.118
  CI (99.9%): [5.779, 10.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.800 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
Iteration   1: 3.409 ±(99.9%) 0.008 ms/op
Iteration   2: 3.414 ±(99.9%) 0.006 ms/op
Iteration   3: 3.416 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.413 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (3.409, 3.413, 3.416), stdev = 0.004
  CI (99.9%): [3.343, 3.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.050 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.005 ms/op
Iteration   1: 3.195 ±(99.9%) 0.010 ms/op
Iteration   2: 3.408 ±(99.9%) 0.004 ms/op
Iteration   3: 3.292 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 1.941 ms/op [Average]
  (min, avg, max) = (3.195, 3.298, 3.408), stdev = 0.106
  CI (99.9%): [1.357, 5.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.198 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.005 ms/op
Iteration   1: 3.554 ±(99.9%) 0.003 ms/op
Iteration   2: 3.405 ±(99.9%) 0.005 ms/op
Iteration   3: 3.424 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.461 ±(99.9%) 1.477 ms/op [Average]
  (min, avg, max) = (3.405, 3.461, 3.554), stdev = 0.081
  CI (99.9%): [1.983, 4.938] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.260 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.012 ms/op
Iteration   1: 4.041 ±(99.9%) 0.004 ms/op
Iteration   2: 3.893 ±(99.9%) 0.011 ms/op
Iteration   3: 3.889 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.941 ±(99.9%) 1.583 ms/op [Average]
  (min, avg, max) = (3.889, 3.941, 4.041), stdev = 0.087
  CI (99.9%): [2.358, 5.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.780 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.011 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  19.523 ms/op
                 createUser·p0.9999: 22.424 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.455 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  19.572 ms/op
                 createUser·p0.9999: 25.108 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  19.143 ms/op
                 createUser·p0.9999: 27.610 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279257
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13850 
    [ 2.500,  5.000) = 259578 
    [ 5.000,  7.500) = 4591 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 165 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     19.447 ms/op
     p(99.9900) =     24.906 ms/op
     p(99.9990) =     28.365 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.371 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  18.993 ms/op
                 existUser·p0.9999: 23.288 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  15.191 ms/op
                 existUser·p0.9999: 24.714 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  16.267 ms/op
                 existUser·p0.9999: 24.055 ms/op
                 existUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290049
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8471 
    [ 2.500,  5.000) = 276244 
    [ 5.000,  7.500) = 4044 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     16.296 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     25.434 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.104 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
Iteration   1: 3.569 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   5.076 ms/op
                 getUser·p0.99:   6.835 ms/op
                 getUser·p0.999:  18.988 ms/op
                 getUser·p0.9999: 21.824 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.342 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  20.006 ms/op
                 getUser·p0.9999: 27.124 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  22.643 ms/op
                 getUser·p0.9999: 27.615 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277845
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8996 
    [ 2.500,  5.000) = 260690 
    [ 5.000,  7.500) = 7032 
    [ 7.500, 10.000) = 653 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     19.086 ms/op
     p(99.9900) =     27.095 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.050 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.013 ms/op
Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 22.986 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.771 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   3.957 ms/op
                 listUser·p0.99:   6.324 ms/op
                 listUser·p0.999:  13.913 ms/op
                 listUser·p0.9999: 17.417 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.905 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248367
  mean =      3.864 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 241507 
    [ 5.000,  7.500) = 5075 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.149 ms/op
     p(99.9900) =     21.894 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.250 ± 3.045  ops/ms
ClientPb.existUser                       thrpt       3   9.737 ± 2.067  ops/ms
ClientPb.getUser                         thrpt       3   9.194 ± 5.780  ops/ms
ClientPb.listUser                        thrpt       3   7.940 ± 2.162  ops/ms
ClientPb.createUser                       avgt       3   3.413 ± 0.069   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 1.941   ms/op
ClientPb.getUser                          avgt       3   3.461 ± 1.477   ms/op
ClientPb.listUser                         avgt       3   3.941 ± 1.583   ms/op
ClientPb.createUser                     sample  279257   3.438 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.447           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.906           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  290049   3.307 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.227           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.296           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.183           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.625           ms/op
ClientPb.getUser                        sample  277845   3.454 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.092           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.086           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.095           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.148           ms/op
ClientPb.listUser                       sample  248367   3.864 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.145           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.149           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.894           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.658           ms/op
