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
# Warmup Iteration   1: 1.949 ops/ms
# Warmup Iteration   2: 5.358 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 9.032 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.080 ±(99.9%) 1.571 ops/ms [Average]
  (min, avg, max) = (9.029, 9.080, 9.180), stdev = 0.086
  CI (99.9%): [7.510, 10.651] (assumes normal distribution)


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
# Warmup Iteration   1: 2.845 ops/ms
# Warmup Iteration   2: 8.104 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.230 ops/ms
Iteration   2: 9.525 ops/ms
Iteration   3: 9.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.408 ±(99.9%) 2.865 ops/ms [Average]
  (min, avg, max) = (9.230, 9.408, 9.525), stdev = 0.157
  CI (99.9%): [6.543, 12.274] (assumes normal distribution)


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
# Warmup Iteration   1: 2.639 ops/ms
# Warmup Iteration   2: 8.233 ops/ms
# Warmup Iteration   3: 8.737 ops/ms
Iteration   1: 9.159 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 9.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.177 ±(99.9%) 1.681 ops/ms [Average]
  (min, avg, max) = (9.095, 9.177, 9.277), stdev = 0.092
  CI (99.9%): [7.496, 10.858] (assumes normal distribution)


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
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 7.282 ops/ms
# Warmup Iteration   3: 7.554 ops/ms
Iteration   1: 7.664 ops/ms
Iteration   2: 7.817 ops/ms
Iteration   3: 7.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.665 ±(99.9%) 2.757 ops/ms [Average]
  (min, avg, max) = (7.514, 7.665, 7.817), stdev = 0.151
  CI (99.9%): [4.908, 10.422] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.532 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.485 ±(99.9%) 0.004 ms/op
Iteration   2: 3.600 ±(99.9%) 0.002 ms/op
Iteration   3: 3.622 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.569 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (3.485, 3.569, 3.622), stdev = 0.073
  CI (99.9%): [2.232, 4.906] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.907 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.006 ms/op
Iteration   1: 3.297 ±(99.9%) 0.004 ms/op
Iteration   2: 3.373 ±(99.9%) 0.004 ms/op
Iteration   3: 3.401 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.357 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.297, 3.357, 3.401), stdev = 0.054
  CI (99.9%): [2.370, 4.344] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.419 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.004 ms/op
Iteration   1: 3.433 ±(99.9%) 0.006 ms/op
Iteration   2: 3.485 ±(99.9%) 0.006 ms/op
Iteration   3: 3.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.471 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.433, 3.471, 3.495), stdev = 0.033
  CI (99.9%): [2.865, 4.077] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.890 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.006 ms/op
Iteration   1: 4.053 ±(99.9%) 0.008 ms/op
Iteration   2: 3.856 ±(99.9%) 0.012 ms/op
Iteration   3: 3.946 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.952 ±(99.9%) 1.797 ms/op [Average]
  (min, avg, max) = (3.856, 3.952, 4.053), stdev = 0.098
  CI (99.9%): [2.155, 5.749] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.181 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
Iteration   1: 3.617 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 30.053 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   2: 3.567 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  22.988 ms/op
                 createUser·p0.9999: 31.988 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 25.362 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270230
  mean =      3.553 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9886 
    [ 2.500,  5.000) = 250614 
    [ 5.000,  7.500) = 7936 
    [ 7.500, 10.000) = 1136 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     30.965 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 8.944 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
Iteration   1: 3.413 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  19.604 ms/op
                 existUser·p0.9999: 25.305 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  22.078 ms/op
                 existUser·p0.9999: 26.366 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.566 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.737 ms/op
                 existUser·p0.999:  10.788 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276915
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10690 
    [ 2.500,  5.000) = 259656 
    [ 5.000,  7.500) = 5154 
    [ 7.500, 10.000) = 948 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.323 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     26.061 ms/op
     p(99.9990) =     27.008 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 10.451 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
Iteration   1: 3.402 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.170 ms/op
                 getUser·p0.999:  14.418 ms/op
                 getUser·p0.9999: 18.847 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.594 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.267 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 24.746 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   3: 3.541 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.119 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  18.817 ms/op
                 getUser·p0.9999: 33.554 ms/op
                 getUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273512
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9936 
    [ 2.500,  5.000) = 253957 
    [ 5.000,  7.500) = 7753 
    [ 7.500, 10.000) = 1184 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     32.571 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 10.586 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.014 ms/op
Iteration   1: 4.106 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.137 ms/op
                 listUser·p0.999:  21.988 ms/op
                 listUser·p0.9999: 25.120 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.153 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.482 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.359 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 22.453 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233333
  mean =      4.115 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 219372 
    [ 5.000,  7.500) = 10714 
    [ 7.500, 10.000) = 1959 
    [10.000, 12.500) = 643 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     26.236 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.080 ± 1.571  ops/ms
ClientPb.existUser                       thrpt       3   9.408 ± 2.865  ops/ms
ClientPb.getUser                         thrpt       3   9.177 ± 1.681  ops/ms
ClientPb.listUser                        thrpt       3   7.665 ± 2.757  ops/ms
ClientPb.createUser                       avgt       3   3.569 ± 1.337   ms/op
ClientPb.existUser                        avgt       3   3.357 ± 0.987   ms/op
ClientPb.getUser                          avgt       3   3.471 ± 0.606   ms/op
ClientPb.listUser                         avgt       3   3.952 ± 1.797   ms/op
ClientPb.createUser                     sample  270230   3.553 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.411           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.792           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.965           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  276915   3.462 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.323           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.061           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.820           ms/op
ClientPb.getUser                        sample  273512   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.386           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.727           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.571           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  233333   4.115 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.482           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.515           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.183           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.378           ms/op
