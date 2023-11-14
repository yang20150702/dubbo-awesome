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
# Warmup Iteration   1: 4.523 ops/ms
# Warmup Iteration   2: 11.873 ops/ms
# Warmup Iteration   3: 12.187 ops/ms
Iteration   1: 12.467 ops/ms
Iteration   2: 12.416 ops/ms
Iteration   3: 12.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.441 ±(99.9%) 0.469 ops/ms [Average]
  (min, avg, max) = (12.416, 12.441, 12.467), stdev = 0.026
  CI (99.9%): [11.972, 12.910] (assumes normal distribution)


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
# Warmup Iteration   1: 8.064 ops/ms
# Warmup Iteration   2: 12.927 ops/ms
# Warmup Iteration   3: 12.920 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.837 ops/ms
Iteration   3: 12.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.879 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (12.814, 12.879, 12.986), stdev = 0.094
  CI (99.9%): [11.173, 14.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.566 ops/ms
# Warmup Iteration   2: 12.197 ops/ms
# Warmup Iteration   3: 12.742 ops/ms
Iteration   1: 12.803 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 12.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.746 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (12.671, 12.746, 12.803), stdev = 0.068
  CI (99.9%): [11.508, 13.984] (assumes normal distribution)


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
# Warmup Iteration   1: 6.883 ops/ms
# Warmup Iteration   2: 10.390 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.669 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.647 ±(99.9%) 0.437 ops/ms [Average]
  (min, avg, max) = (10.621, 10.647, 10.669), stdev = 0.024
  CI (99.9%): [10.210, 11.084] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.003 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
Iteration   3: 2.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.535, 2.548, 2.561), stdev = 0.013
  CI (99.9%): [2.308, 2.788] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.003 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.480 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.467, 2.480, 2.489), stdev = 0.012
  CI (99.9%): [2.262, 2.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.526 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.509, 2.526, 2.545), stdev = 0.018
  CI (99.9%): [2.202, 2.850] (assumes normal distribution)


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 2.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.994 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.979, 2.994, 3.002), stdev = 0.013
  CI (99.9%): [2.754, 3.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 14.032 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.941 ms/op
                 createUser·p0.999:  10.062 ms/op
                 createUser·p0.9999: 14.515 ms/op
                 createUser·p1.00:   15.712 ms/op

Iteration   3: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.582 ms/op
                 createUser·p0.9999: 10.594 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375337
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 178707 
    [ 2.500,  3.750) = 191214 
    [ 3.750,  5.000) = 4065 
    [ 5.000,  6.250) = 735 
    [ 6.250,  7.500) = 142 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      9.170 ms/op
     p(99.9900) =     14.089 ms/op
     p(99.9990) =     15.141 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  5.924 ms/op
                 existUser·p0.9999: 17.172 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.779 ms/op
                 existUser·p0.9999: 13.320 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  7.369 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387943
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 188579 
    [ 2.500,  3.750) = 195485 
    [ 3.750,  5.000) = 2921 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     14.110 ms/op
     p(99.9990) =     17.404 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  12.243 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  10.311 ms/op
                 getUser·p0.9999: 13.281 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  6.883 ms/op
                 getUser·p0.9999: 11.080 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381395
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 188065 
    [ 2.500,  3.750) = 188202 
    [ 3.750,  5.000) = 3975 
    [ 5.000,  6.250) = 512 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      9.611 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.009 ms/op
Iteration   1: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 12.026 ms/op
                 listUser·p1.00:   12.943 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.908 ms/op
                 listUser·p0.9999: 12.884 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.033 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318083
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 92409 
    [ 2.500,  3.750) = 185798 
    [ 3.750,  5.000) = 32294 
    [ 5.000,  6.250) = 6014 
    [ 6.250,  7.500) = 720 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.534 ms/op
     p(99.9900) =     12.111 ms/op
     p(99.9990) =     13.118 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.441 ± 0.469  ops/ms
ClientPb.existUser                       thrpt       3  12.879 ± 1.706  ops/ms
ClientPb.getUser                         thrpt       3  12.746 ± 1.238  ops/ms
ClientPb.listUser                        thrpt       3  10.647 ± 0.437  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.240   ms/op
ClientPb.existUser                        avgt       3   2.480 ± 0.218   ms/op
ClientPb.getUser                          avgt       3   2.526 ± 0.324   ms/op
ClientPb.listUser                         avgt       3   2.994 ± 0.240   ms/op
ClientPb.createUser                     sample  375337   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.873           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.089           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.712           ms/op
ClientPb.existUser                      sample  387943   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.895           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.652           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.110           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.465           ms/op
ClientPb.getUser                        sample  381395   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.896           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.611           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.959           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  318083   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.783           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.534           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
