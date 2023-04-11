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
# Warmup Iteration   1: 2.157 ops/ms
# Warmup Iteration   2: 5.507 ops/ms
# Warmup Iteration   3: 8.371 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 9.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.328 ±(99.9%) 3.562 ops/ms [Average]
  (min, avg, max) = (9.115, 9.328, 9.500), stdev = 0.195
  CI (99.9%): [5.765, 12.890] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.352 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.724 ops/ms
Iteration   3: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.603 ±(99.9%) 1.978 ops/ms [Average]
  (min, avg, max) = (9.515, 9.603, 9.724), stdev = 0.108
  CI (99.9%): [7.625, 11.581] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 8.996 ops/ms
Iteration   1: 9.332 ops/ms
Iteration   2: 9.390 ops/ms
Iteration   3: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.406 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (9.332, 9.406, 9.497), stdev = 0.083
  CI (99.9%): [7.883, 10.929] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.827 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.126 ±(99.9%) 2.014 ops/ms [Average]
  (min, avg, max) = (8.012, 8.126, 8.232), stdev = 0.110
  CI (99.9%): [6.112, 10.140] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.996 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.005 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
Iteration   2: 3.405 ±(99.9%) 0.004 ms/op
Iteration   3: 3.518 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.435 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (3.382, 3.435, 3.518), stdev = 0.073
  CI (99.9%): [2.103, 4.767] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.814 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.005 ms/op
Iteration   1: 3.256 ±(99.9%) 0.006 ms/op
Iteration   2: 3.373 ±(99.9%) 0.011 ms/op
Iteration   3: 3.296 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.256, 3.308, 3.373), stdev = 0.060
  CI (99.9%): [2.220, 4.397] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.464 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.005 ms/op
Iteration   1: 3.368 ±(99.9%) 0.006 ms/op
Iteration   2: 3.504 ±(99.9%) 0.007 ms/op
Iteration   3: 3.487 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.453 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.368, 3.453, 3.504), stdev = 0.074
  CI (99.9%): [2.097, 4.809] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.668 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.009 ms/op
Iteration   1: 3.901 ±(99.9%) 0.008 ms/op
Iteration   2: 3.904 ±(99.9%) 0.010 ms/op
Iteration   3: 3.876 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.893 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.876, 3.893, 3.904), stdev = 0.015
  CI (99.9%): [3.613, 4.174] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.207 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 22.332 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  22.876 ms/op
                 createUser·p0.9999: 27.346 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 3.343 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.549 ms/op
                 createUser·p0.9999: 25.326 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283471
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7669 
    [ 2.500,  5.000) = 270047 
    [ 5.000,  7.500) = 4589 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     19.809 ms/op
     p(99.9900) =     25.646 ms/op
     p(99.9990) =     28.655 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.784 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
Iteration   1: 3.309 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 22.588 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  18.464 ms/op
                 existUser·p0.9999: 25.035 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.109 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 24.805 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289211
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11224 
    [ 2.500,  5.000) = 272093 
    [ 5.000,  7.500) = 4662 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     25.959 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 9.084 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.011 ms/op
Iteration   1: 3.471 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  19.787 ms/op
                 getUser·p0.9999: 25.145 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   2: 3.530 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.107 ms/op
                 getUser·p0.999:  20.063 ms/op
                 getUser·p0.9999: 33.553 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 3.291 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.763 ms/op
                 getUser·p0.9999: 26.013 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279873
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1371 
    [ 2.500,  5.000) = 271385 
    [ 5.000,  7.500) = 5813 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 11.054 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.015 ms/op
Iteration   1: 3.921 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  18.556 ms/op
                 listUser·p0.9999: 23.854 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 3.974 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 17.234 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.950 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.905 ms/op
                 listUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243182
  mean =      3.948 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 236300 
    [ 5.000,  7.500) = 5177 
    [ 7.500, 10.000) = 910 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.982 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     22.775 ms/op
     p(99.9990) =     24.636 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.328 ± 3.562  ops/ms
ClientPb.existUser                       thrpt       3   9.603 ± 1.978  ops/ms
ClientPb.getUser                         thrpt       3   9.406 ± 1.523  ops/ms
ClientPb.listUser                        thrpt       3   8.126 ± 2.014  ops/ms
ClientPb.createUser                       avgt       3   3.435 ± 1.332   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 1.088   ms/op
ClientPb.getUser                          avgt       3   3.453 ± 1.356   ms/op
ClientPb.listUser                         avgt       3   3.893 ± 0.280   ms/op
ClientPb.createUser                     sample  283471   3.384 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.430           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.646           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.164           ms/op
ClientPb.existUser                      sample  289211   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.300           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.830           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.707           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.018           ms/op
ClientPb.getUser                        sample  279873   3.427 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.651           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.694           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.506           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  243182   3.948 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.982           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.991           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.775           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.166           ms/op
