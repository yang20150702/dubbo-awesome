# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.832 ops/ms
# Warmup Iteration   2: 11.865 ops/ms
# Warmup Iteration   3: 12.113 ops/ms
Iteration   1: 12.191 ops/ms
Iteration   2: 12.317 ops/ms
Iteration   3: 12.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.306 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (12.191, 12.306, 12.412), stdev = 0.111
  CI (99.9%): [10.281, 14.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.268 ops/ms
# Warmup Iteration   2: 12.961 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 13.177 ops/ms
Iteration   2: 13.466 ops/ms
Iteration   3: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.308 ±(99.9%) 2.669 ops/ms [Average]
  (min, avg, max) = (13.177, 13.308, 13.466), stdev = 0.146
  CI (99.9%): [10.638, 15.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.881 ops/ms
# Warmup Iteration   2: 12.465 ops/ms
# Warmup Iteration   3: 12.690 ops/ms
Iteration   1: 12.867 ops/ms
Iteration   2: 12.807 ops/ms
Iteration   3: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.838 ±(99.9%) 0.553 ops/ms [Average]
  (min, avg, max) = (12.807, 12.838, 12.867), stdev = 0.030
  CI (99.9%): [12.285, 13.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.605 ops/ms
# Warmup Iteration   2: 10.525 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.495 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.561 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (10.495, 10.561, 10.608), stdev = 0.059
  CI (99.9%): [9.485, 11.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.004 ms/op
Iteration   1: 2.623 ±(99.9%) 0.005 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.576 ±(99.9%) 0.791 ms/op [Average]
  (min, avg, max) = (2.537, 2.576, 2.623), stdev = 0.043
  CI (99.9%): [1.785, 3.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.007 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.006 ms/op
Iteration   3: 2.406 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.406, 2.432, 2.458), stdev = 0.026
  CI (99.9%): [1.963, 2.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.474, 2.492, 2.510), stdev = 0.018
  CI (99.9%): [2.159, 2.825] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.642 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.004 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
Iteration   3: 3.040 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.027 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (3.005, 3.027, 3.040), stdev = 0.019
  CI (99.9%): [2.675, 3.379] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.597 ±(99.9%) 0.006 ms/op
Iteration   1: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  11.596 ms/op
                 createUser·p0.9999: 13.770 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 11.700 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 12.373 ms/op
                 createUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373071
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 176064 
    [ 2.500,  3.750) = 192606 
    [ 3.750,  5.000) = 3341 
    [ 5.000,  6.250) = 556 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.839 ms/op
     p(99.9000) =      9.436 ms/op
     p(99.9900) =     13.528 ms/op
     p(99.9990) =     14.263 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  11.005 ms/op
                 existUser·p0.9999: 13.612 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  8.558 ms/op
                 existUser·p0.9999: 12.097 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  5.716 ms/op
                 existUser·p0.9999: 11.887 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381265
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 187383 
    [ 2.500,  3.750) = 190359 
    [ 3.750,  5.000) = 2597 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.357 ms/op
     p(99.9900) =     12.812 ms/op
     p(99.9990) =     14.539 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  5.620 ms/op
                 getUser·p0.9999: 16.335 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 11.928 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377413
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 185082 
    [ 2.500,  3.750) = 187075 
    [ 3.750,  5.000) = 3691 
    [ 5.000,  6.250) = 1139 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      6.218 ms/op
     p(99.9900) =     14.934 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.567 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.396 ms/op
                 listUser·p0.9999: 10.850 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.986 ms/op
                 listUser·p0.9999: 11.583 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.224 ms/op
                 listUser·p0.9999: 12.331 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312184
  mean =      3.072 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 80792 
    [ 2.500,  3.750) = 188678 
    [ 3.750,  5.000) = 35056 
    [ 5.000,  6.250) = 6186 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 155 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.614 ms/op
     p(99.9900) =     11.753 ms/op
     p(99.9990) =     12.481 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.306 ± 2.025  ops/ms
ClientPb.existUser                       thrpt       3  13.308 ± 2.669  ops/ms
ClientPb.getUser                         thrpt       3  12.838 ± 0.553  ops/ms
ClientPb.listUser                        thrpt       3  10.561 ± 1.076  ops/ms
ClientPb.createUser                       avgt       3   2.576 ± 0.791   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.469   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.333   ms/op
ClientPb.listUser                         avgt       3   3.027 ± 0.352   ms/op
ClientPb.createUser                     sample  373071   2.571 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.686           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.839           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.436           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.528           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  381265   2.515 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.766           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.357           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  377413   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.934           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  312184   3.072 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.811           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.614           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.753           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.517           ms/op
