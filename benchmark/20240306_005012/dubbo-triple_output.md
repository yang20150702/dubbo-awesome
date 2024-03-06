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
# Warmup Iteration   1: 5.023 ops/ms
# Warmup Iteration   2: 12.406 ops/ms
# Warmup Iteration   3: 12.655 ops/ms
Iteration   1: 12.882 ops/ms
Iteration   2: 12.779 ops/ms
Iteration   3: 12.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.854 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (12.779, 12.854, 12.901), stdev = 0.066
  CI (99.9%): [11.655, 14.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ops/ms
# Warmup Iteration   2: 13.186 ops/ms
# Warmup Iteration   3: 13.398 ops/ms
Iteration   1: 13.261 ops/ms
Iteration   2: 13.383 ops/ms
Iteration   3: 13.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.342 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (13.261, 13.342, 13.383), stdev = 0.070
  CI (99.9%): [12.061, 14.623] (assumes normal distribution)


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
# Warmup Iteration   1: 7.835 ops/ms
# Warmup Iteration   2: 13.115 ops/ms
# Warmup Iteration   3: 13.187 ops/ms
Iteration   1: 13.321 ops/ms
Iteration   2: 13.339 ops/ms
Iteration   3: 13.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.353 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (13.321, 13.353, 13.399), stdev = 0.041
  CI (99.9%): [12.603, 14.103] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.809 ops/ms
# Warmup Iteration   2: 10.789 ops/ms
# Warmup Iteration   3: 10.886 ops/ms
Iteration   1: 10.885 ops/ms
Iteration   2: 10.887 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.892 ±(99.9%) 0.176 ops/ms [Average]
  (min, avg, max) = (10.885, 10.892, 10.903), stdev = 0.010
  CI (99.9%): [10.716, 11.067] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.453 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.439, 2.453, 2.462), stdev = 0.012
  CI (99.9%): [2.236, 2.669] (assumes normal distribution)


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.401 ±(99.9%) 0.004 ms/op
Iteration   1: 2.366 ±(99.9%) 0.003 ms/op
Iteration   2: 2.370 ±(99.9%) 0.003 ms/op
Iteration   3: 2.373 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.370 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (2.366, 2.370, 2.373), stdev = 0.003
  CI (99.9%): [2.306, 2.433] (assumes normal distribution)


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.396 ±(99.9%) 0.004 ms/op
Iteration   3: 2.406 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.412 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.396, 2.412, 2.432), stdev = 0.018
  CI (99.9%): [2.078, 2.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.919 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.004 ms/op
Iteration   1: 2.918 ±(99.9%) 0.006 ms/op
Iteration   2: 2.922 ±(99.9%) 0.006 ms/op
Iteration   3: 2.950 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.930 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (2.918, 2.930, 2.950), stdev = 0.017
  CI (99.9%): [2.613, 3.247] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  6.363 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.539 ms/op
                 createUser·p0.999:  7.320 ms/op
                 createUser·p0.9999: 12.468 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  8.473 ms/op
                 createUser·p0.9999: 11.370 ms/op
                 createUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 392530
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 196967 
    [ 2.500,  3.750) = 191595 
    [ 3.750,  5.000) = 3197 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.429 ms/op
     p(99.9900) =     13.099 ms/op
     p(99.9990) =     14.272 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.392 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.388 ms/op
                 existUser·p0.999:  4.965 ms/op
                 existUser·p0.9999: 13.227 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  7.870 ms/op
                 existUser·p0.9999: 13.037 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  8.928 ms/op
                 existUser·p0.9999: 12.046 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398595
  mean =      2.405 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 201632 
    [ 2.500,  3.750) = 194268 
    [ 3.750,  5.000) = 1974 
    [ 5.000,  6.250) = 209 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     13.011 ms/op
     p(99.9990) =     13.878 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  6.652 ms/op
                 getUser·p0.9999: 13.416 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  10.595 ms/op
                 getUser·p0.9999: 15.417 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  6.096 ms/op
                 getUser·p0.9999: 11.859 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392005
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 198794 
    [ 2.500,  3.750) = 188478 
    [ 3.750,  5.000) = 3443 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     14.660 ms/op
     p(99.9990) =     15.582 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.008 ms/op
Iteration   1: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.958 ms/op
                 listUser·p0.9999: 10.065 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 2.943 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.207 ms/op

Iteration   3: 2.920 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.881 ms/op
                 listUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326342
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 105876 
    [ 2.500,  3.750) = 184574 
    [ 3.750,  5.000) = 29369 
    [ 5.000,  6.250) = 5176 
    [ 6.250,  7.500) = 559 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.869 ms/op
     p(99.9990) =     11.207 ms/op
     p(99.9999) =     11.780 ms/op
    p(100.0000) =     11.780 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.854 ± 1.199  ops/ms
ClientPb.existUser                       thrpt       3  13.342 ± 1.281  ops/ms
ClientPb.getUser                         thrpt       3  13.353 ± 0.750  ops/ms
ClientPb.listUser                        thrpt       3  10.892 ± 0.176  ops/ms
ClientPb.createUser                       avgt       3   2.453 ± 0.216   ms/op
ClientPb.existUser                        avgt       3   2.370 ± 0.064   ms/op
ClientPb.getUser                          avgt       3   2.412 ± 0.334   ms/op
ClientPb.listUser                         avgt       3   2.930 ± 0.317   ms/op
ClientPb.createUser                     sample  392530   2.443 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.771           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.494           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.429           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  398595   2.405 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.967           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.209           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.011           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.237           ms/op
ClientPb.getUser                        sample  392005   2.447 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.823           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.970           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.520           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.660           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  326342   2.939 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.869           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.780           ms/op
