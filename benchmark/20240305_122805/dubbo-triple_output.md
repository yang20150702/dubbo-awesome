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
# Warmup Iteration   1: 4.661 ops/ms
# Warmup Iteration   2: 11.821 ops/ms
# Warmup Iteration   3: 12.345 ops/ms
Iteration   1: 12.520 ops/ms
Iteration   2: 12.799 ops/ms
Iteration   3: 12.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.726 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (12.520, 12.726, 12.858), stdev = 0.181
  CI (99.9%): [9.429, 16.022] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ops/ms
# Warmup Iteration   2: 13.236 ops/ms
# Warmup Iteration   3: 13.270 ops/ms
Iteration   1: 13.220 ops/ms
Iteration   2: 13.015 ops/ms
Iteration   3: 13.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.103 ±(99.9%) 1.922 ops/ms [Average]
  (min, avg, max) = (13.015, 13.103, 13.220), stdev = 0.105
  CI (99.9%): [11.181, 15.025] (assumes normal distribution)


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
# Warmup Iteration   1: 8.031 ops/ms
# Warmup Iteration   2: 12.919 ops/ms
# Warmup Iteration   3: 13.032 ops/ms
Iteration   1: 13.169 ops/ms
Iteration   2: 13.110 ops/ms
Iteration   3: 13.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.106 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (13.038, 13.106, 13.169), stdev = 0.066
  CI (99.9%): [11.909, 14.303] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.743 ops/ms
# Warmup Iteration   2: 10.647 ops/ms
# Warmup Iteration   3: 10.713 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.752 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.699 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (10.596, 10.699, 10.752), stdev = 0.090
  CI (99.9%): [9.064, 12.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.469 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.460, 2.469, 2.476), stdev = 0.009
  CI (99.9%): [2.312, 2.626] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.003 ms/op
Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.415 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (2.411, 2.415, 2.418), stdev = 0.003
  CI (99.9%): [2.352, 2.478] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.003 ms/op
Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
Iteration   3: 2.413 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.421 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.409, 2.421, 2.440), stdev = 0.017
  CI (99.9%): [2.118, 2.723] (assumes normal distribution)


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (3.031, 3.038, 3.046), stdev = 0.008
  CI (99.9%): [2.893, 3.183] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 13.566 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.945 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  5.834 ms/op
                 createUser·p0.9999: 12.017 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.204 ms/op
                 createUser·p0.9999: 14.607 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 394107
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 195631 
    [ 2.500,  3.750) = 194726 
    [ 3.750,  5.000) = 2834 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     16.731 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
Iteration   1: 2.383 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.367 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.243 ms/op
                 existUser·p0.9999: 14.657 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.064 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.380 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  7.680 ms/op
                 existUser·p0.9999: 12.250 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400674
  mean =      2.394 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 217291 
    [ 2.500,  3.750) = 180182 
    [ 3.750,  5.000) = 2329 
    [ 5.000,  6.250) = 287 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.388 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     15.007 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  7.002 ms/op
                 getUser·p0.9999: 13.762 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.447 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   2.376 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.428 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.834 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.388 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  7.522 ms/op
                 getUser·p0.9999: 10.797 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392746
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 243 
    [ 1.250,  2.500) = 211951 
    [ 2.500,  3.750) = 172564 
    [ 3.750,  5.000) = 6951 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.400 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      7.602 ms/op
     p(99.9900) =     12.972 ms/op
     p(99.9990) =     14.336 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.008 ms/op
Iteration   1: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.227 ms/op
                 listUser·p0.9999: 14.254 ms/op
                 listUser·p1.00:   14.811 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.537 ms/op
                 listUser·p0.9999: 11.328 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   3: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.875 ms/op
                 listUser·p0.9999: 10.603 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324018
  mean =      2.960 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 188 
    [ 1.250,  2.500) = 104143 
    [ 2.500,  3.750) = 182687 
    [ 3.750,  5.000) = 29949 
    [ 5.000,  6.250) = 5803 
    [ 6.250,  7.500) = 591 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     12.111 ms/op
     p(99.9990) =     14.701 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.726 ± 3.297  ops/ms
ClientPb.existUser                       thrpt       3  13.103 ± 1.922  ops/ms
ClientPb.getUser                         thrpt       3  13.106 ± 1.197  ops/ms
ClientPb.listUser                        thrpt       3  10.699 ± 1.636  ops/ms
ClientPb.createUser                       avgt       3   2.469 ± 0.157   ms/op
ClientPb.existUser                        avgt       3   2.415 ± 0.063   ms/op
ClientPb.getUser                          avgt       3   2.421 ± 0.303   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.145   ms/op
ClientPb.createUser                     sample  394107   2.434 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.878           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.568           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.628           ms/op
ClientPb.existUser                      sample  400674   2.394 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.521           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.388           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.221           ms/op
ClientPb.getUser                        sample  392746   2.442 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.652           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.602           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.972           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.418           ms/op
ClientPb.listUser                       sample  324018   2.960 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.752           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.811           ms/op
