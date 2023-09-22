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
# Warmup Iteration   1: 2.446 ops/ms
# Warmup Iteration   2: 6.686 ops/ms
# Warmup Iteration   3: 9.188 ops/ms
Iteration   1: 9.578 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.627 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (9.578, 9.627, 9.702), stdev = 0.066
  CI (99.9%): [8.427, 10.827] (assumes normal distribution)


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
# Warmup Iteration   1: 3.525 ops/ms
# Warmup Iteration   2: 9.309 ops/ms
# Warmup Iteration   3: 10.050 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 10.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.242 ±(99.9%) 2.041 ops/ms [Average]
  (min, avg, max) = (10.169, 10.242, 10.370), stdev = 0.112
  CI (99.9%): [8.201, 12.282] (assumes normal distribution)


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
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 8.269 ops/ms
# Warmup Iteration   3: 9.855 ops/ms
Iteration   1: 9.904 ops/ms
Iteration   2: 9.854 ops/ms
Iteration   3: 9.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.890 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (9.854, 9.890, 9.912), stdev = 0.032
  CI (99.9%): [9.311, 10.468] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.724 ops/ms
# Warmup Iteration   2: 7.537 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.356 ops/ms
Iteration   2: 8.265 ops/ms
Iteration   3: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.334 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (8.265, 8.334, 8.381), stdev = 0.061
  CI (99.9%): [7.218, 9.450] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.765 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.007 ms/op
Iteration   1: 3.223 ±(99.9%) 0.002 ms/op
Iteration   2: 3.313 ±(99.9%) 0.004 ms/op
Iteration   3: 3.296 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.277 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.223, 3.277, 3.313), stdev = 0.048
  CI (99.9%): [2.403, 4.152] (assumes normal distribution)


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
# Warmup Iteration   1: 7.784 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.004 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.146 ±(99.9%) 0.061 ms/op [Average]
  (min, avg, max) = (3.142, 3.146, 3.148), stdev = 0.003
  CI (99.9%): [3.085, 3.207] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.832 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.002 ms/op
Iteration   1: 3.230 ±(99.9%) 0.002 ms/op
Iteration   2: 3.225 ±(99.9%) 0.004 ms/op
Iteration   3: 3.188 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.214 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (3.188, 3.214, 3.230), stdev = 0.023
  CI (99.9%): [2.793, 3.635] (assumes normal distribution)


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
# Warmup Iteration   1: 8.255 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.003 ms/op
Iteration   1: 3.917 ±(99.9%) 0.003 ms/op
Iteration   2: 3.819 ±(99.9%) 0.006 ms/op
Iteration   3: 3.861 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.865 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (3.819, 3.865, 3.917), stdev = 0.049
  CI (99.9%): [2.971, 4.759] (assumes normal distribution)


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
# Warmup Iteration   1: 7.089 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.599 ms/op
                 createUser·p0.999:  10.337 ms/op
                 createUser·p0.9999: 20.551 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  13.551 ms/op
                 createUser·p0.9999: 22.329 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.396 ms/op
                 createUser·p0.999:  14.974 ms/op
                 createUser·p0.9999: 31.326 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294836
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13953 
    [ 2.500,  5.000) = 276940 
    [ 5.000,  7.500) = 3141 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     14.866 ms/op
     p(99.9900) =     28.960 ms/op
     p(99.9990) =     31.711 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 7.650 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  10.487 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  14.483 ms/op
                 existUser·p0.9999: 24.386 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  12.791 ms/op
                 existUser·p0.9999: 24.510 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297334
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16117 
    [ 2.500,  5.000) = 274627 
    [ 5.000,  7.500) = 5676 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     12.408 ms/op
     p(99.9900) =     24.060 ms/op
     p(99.9990) =     25.396 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 7.400 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
Iteration   1: 3.191 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.336 ms/op
                 getUser·p0.999:  14.523 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  20.515 ms/op
                 getUser·p0.9999: 24.711 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.334 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.855 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 19.091 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295728
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13500 
    [ 2.500,  5.000) = 276981 
    [ 5.000,  7.500) = 4466 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     14.553 ms/op
     p(99.9900) =     23.574 ms/op
     p(99.9990) =     25.073 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 8.438 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 3.861 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.619 ms/op
                 listUser·p0.9999: 20.250 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 3.849 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 15.729 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.873 ms/op
                 listUser·p0.9999: 13.872 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249329
  mean =      3.849 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 243270 
    [ 5.000,  7.500) = 4462 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.413 ms/op
     p(99.9900) =     19.106 ms/op
     p(99.9990) =     20.563 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.627 ± 1.200  ops/ms
ClientPb.existUser                       thrpt       3  10.242 ± 2.041  ops/ms
ClientPb.getUser                         thrpt       3   9.890 ± 0.579  ops/ms
ClientPb.listUser                        thrpt       3   8.334 ± 1.116  ops/ms
ClientPb.createUser                       avgt       3   3.277 ± 0.875   ms/op
ClientPb.existUser                        avgt       3   3.146 ± 0.061   ms/op
ClientPb.getUser                          avgt       3   3.214 ± 0.421   ms/op
ClientPb.listUser                         avgt       3   3.865 ± 0.894   ms/op
ClientPb.createUser                     sample  294836   3.255 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.786           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.866           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.960           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  297334   3.228 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.426           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.931           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.408           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.060           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.723           ms/op
ClientPb.getUser                        sample  295728   3.245 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.553           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.574           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.297           ms/op
ClientPb.listUser                       sample  249329   3.849 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.693           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.413           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.106           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.103           ms/op
