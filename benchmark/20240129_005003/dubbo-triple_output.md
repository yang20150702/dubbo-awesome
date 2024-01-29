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
# Warmup Iteration   1: 4.734 ops/ms
# Warmup Iteration   2: 12.158 ops/ms
# Warmup Iteration   3: 12.405 ops/ms
Iteration   1: 12.698 ops/ms
Iteration   2: 12.701 ops/ms
Iteration   3: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.746 ±(99.9%) 1.471 ops/ms [Average]
  (min, avg, max) = (12.698, 12.746, 12.839), stdev = 0.081
  CI (99.9%): [11.274, 14.217] (assumes normal distribution)


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
# Warmup Iteration   1: 8.952 ops/ms
# Warmup Iteration   2: 12.908 ops/ms
# Warmup Iteration   3: 13.276 ops/ms
Iteration   1: 13.276 ops/ms
Iteration   2: 13.321 ops/ms
Iteration   3: 13.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.272 ±(99.9%) 0.954 ops/ms [Average]
  (min, avg, max) = (13.217, 13.272, 13.321), stdev = 0.052
  CI (99.9%): [12.317, 14.226] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ops/ms
# Warmup Iteration   2: 12.703 ops/ms
# Warmup Iteration   3: 12.967 ops/ms
Iteration   1: 13.075 ops/ms
Iteration   2: 12.969 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.047 ±(99.9%) 1.247 ops/ms [Average]
  (min, avg, max) = (12.969, 13.047, 13.097), stdev = 0.068
  CI (99.9%): [11.800, 14.294] (assumes normal distribution)


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
# Warmup Iteration   1: 6.551 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.716 ops/ms
Iteration   1: 10.865 ops/ms
Iteration   2: 10.897 ops/ms
Iteration   3: 10.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.887 ±(99.9%) 0.350 ops/ms [Average]
  (min, avg, max) = (10.865, 10.887, 10.899), stdev = 0.019
  CI (99.9%): [10.537, 11.237] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.493 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (2.454, 2.493, 2.538), stdev = 0.042
  CI (99.9%): [1.721, 3.266] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.407, 2.418, 2.427), stdev = 0.010
  CI (99.9%): [2.231, 2.605] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.474 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.468, 2.474, 2.484), stdev = 0.008
  CI (99.9%): [2.321, 2.627] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
Iteration   3: 2.953 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.953, 2.969, 2.985), stdev = 0.016
  CI (99.9%): [2.677, 3.261] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  7.687 ms/op
                 createUser·p0.9999: 13.060 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  7.983 ms/op
                 createUser·p0.9999: 11.790 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 10.099 ms/op
                 createUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385207
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 186761 
    [ 2.500,  3.750) = 193806 
    [ 3.750,  5.000) = 3638 
    [ 5.000,  6.250) = 498 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      7.343 ms/op
     p(99.9900) =     12.483 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 13.252 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.642 ms/op
                 existUser·p0.9999: 10.224 ms/op
                 existUser·p1.00:   11.370 ms/op

Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.025 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396243
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 200420 
    [ 2.500,  3.750) = 192873 
    [ 3.750,  5.000) = 2099 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      7.313 ms/op
     p(99.9900) =     12.771 ms/op
     p(99.9990) =     14.709 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  10.175 ms/op
                 getUser·p0.9999: 13.105 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  9.071 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.583 ms/op
                 getUser·p0.999:  5.660 ms/op
                 getUser·p0.9999: 10.633 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384178
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 191252 
    [ 2.500,  3.750) = 187138 
    [ 3.750,  5.000) = 4241 
    [ 5.000,  6.250) = 961 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      8.566 ms/op
     p(99.9900) =     13.084 ms/op
     p(99.9990) =     13.989 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.133 ms/op
                 listUser·p0.9999: 10.835 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.275 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.327 ms/op
                 listUser·p0.9999: 11.276 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.272 ms/op
                 listUser·p0.9999: 13.145 ms/op
                 listUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321526
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 98224 
    [ 2.500,  3.750) = 186226 
    [ 3.750,  5.000) = 29693 
    [ 5.000,  6.250) = 6021 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.445 ms/op
     p(99.9990) =     13.745 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.746 ± 1.471  ops/ms
ClientPb.existUser                       thrpt       3  13.272 ± 0.954  ops/ms
ClientPb.getUser                         thrpt       3  13.047 ± 1.247  ops/ms
ClientPb.listUser                        thrpt       3  10.887 ± 0.350  ops/ms
ClientPb.createUser                       avgt       3   2.493 ± 0.773   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.187   ms/op
ClientPb.getUser                          avgt       3   2.474 ± 0.153   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.292   ms/op
ClientPb.createUser                     sample  385207   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.603           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.343           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.548           ms/op
ClientPb.existUser                      sample  396243   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.313           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.771           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.172           ms/op
ClientPb.getUser                        sample  384178   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.725           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.566           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.084           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  321526   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.445           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.877           ms/op
