# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ops/ms
# Warmup Iteration   2: 12.124 ops/ms
# Warmup Iteration   3: 12.254 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.594 ops/ms
Iteration   3: 12.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.593 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (12.549, 12.593, 12.635), stdev = 0.043
  CI (99.9%): [11.813, 13.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.998 ops/ms
# Warmup Iteration   2: 12.711 ops/ms
# Warmup Iteration   3: 13.005 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 12.971 ops/ms
Iteration   3: 12.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.987 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (12.945, 12.987, 13.044), stdev = 0.051
  CI (99.9%): [12.048, 13.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.425 ops/ms
# Warmup Iteration   2: 12.252 ops/ms
# Warmup Iteration   3: 12.549 ops/ms
Iteration   1: 12.537 ops/ms
Iteration   2: 12.481 ops/ms
Iteration   3: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.603 ±(99.9%) 3.020 ops/ms [Average]
  (min, avg, max) = (12.481, 12.603, 12.791), stdev = 0.166
  CI (99.9%): [9.583, 15.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.359 ops/ms
# Warmup Iteration   2: 10.286 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.359 ops/ms
Iteration   2: 10.187 ops/ms
Iteration   3: 10.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.309 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (10.187, 10.309, 10.380), stdev = 0.106
  CI (99.9%): [8.381, 12.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.004 ms/op
Iteration   1: 2.591 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.572 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.574 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.558, 2.574, 2.591), stdev = 0.017
  CI (99.9%): [2.267, 2.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
Iteration   3: 2.437 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.437, 2.445, 2.456), stdev = 0.010
  CI (99.9%): [2.267, 2.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.003 ms/op
Iteration   2: 2.482 ±(99.9%) 0.003 ms/op
Iteration   3: 2.523 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.482, 2.498, 2.523), stdev = 0.022
  CI (99.9%): [2.103, 2.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.708 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.003, 3.016, 3.035), stdev = 0.017
  CI (99.9%): [2.714, 3.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.677 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  11.867 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   4.069 ms/op
                 createUser·p0.999:  9.723 ms/op
                 createUser·p0.9999: 14.686 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.431 ms/op
                 createUser·p0.9999: 11.458 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379203
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 181616 
    [ 2.500,  3.750) = 193035 
    [ 3.750,  5.000) = 3426 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.451 ms/op
     p(99.9900) =     14.092 ms/op
     p(99.9990) =     14.871 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  6.052 ms/op
                 existUser·p0.9999: 16.721 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.654 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  6.256 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380488
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 184377 
    [ 2.500,  3.750) = 191586 
    [ 3.750,  5.000) = 3329 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     17.406 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  12.045 ms/op
                 getUser·p0.9999: 16.288 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  9.853 ms/op
                 getUser·p0.9999: 14.557 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.641 ms/op
                 getUser·p0.9999: 12.426 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378789
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 185293 
    [ 2.500,  3.750) = 188063 
    [ 3.750,  5.000) = 4168 
    [ 5.000,  6.250) = 742 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.687 ms/op
     p(99.9900) =     14.684 ms/op
     p(99.9990) =     16.791 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.891 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.174 ms/op
                 listUser·p1.00:   11.010 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.628 ms/op
                 listUser·p0.9999: 11.542 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.204 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315513
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 87859 
    [ 2.500,  3.750) = 186049 
    [ 3.750,  5.000) = 33157 
    [ 5.000,  6.250) = 6907 
    [ 6.250,  7.500) = 770 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     11.936 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.593 ± 0.780  ops/ms
ClientPb.existUser                       thrpt       3  12.987 ± 0.939  ops/ms
ClientPb.getUser                         thrpt       3  12.603 ± 3.020  ops/ms
ClientPb.listUser                        thrpt       3  10.309 ± 1.928  ops/ms
ClientPb.createUser                       avgt       3   2.574 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.179   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.395   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.302   ms/op
ClientPb.createUser                     sample  379203   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.451           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.092           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.188           ms/op
ClientPb.existUser                      sample  380488   2.520 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.956           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.498           ms/op
ClientPb.getUser                        sample  378789   2.532 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.687           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.684           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.400           ms/op
ClientPb.listUser                       sample  315513   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.940           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
