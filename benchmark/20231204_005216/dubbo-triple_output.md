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
# Warmup Iteration   1: 4.399 ops/ms
# Warmup Iteration   2: 11.726 ops/ms
# Warmup Iteration   3: 12.203 ops/ms
Iteration   1: 12.347 ops/ms
Iteration   2: 12.474 ops/ms
Iteration   3: 12.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.464 ±(99.9%) 2.056 ops/ms [Average]
  (min, avg, max) = (12.347, 12.464, 12.571), stdev = 0.113
  CI (99.9%): [10.408, 14.520] (assumes normal distribution)


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
# Warmup Iteration   1: 8.292 ops/ms
# Warmup Iteration   2: 12.859 ops/ms
# Warmup Iteration   3: 13.050 ops/ms
Iteration   1: 12.885 ops/ms
Iteration   2: 13.011 ops/ms
Iteration   3: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.912 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (12.840, 12.912, 13.011), stdev = 0.088
  CI (99.9%): [11.303, 14.521] (assumes normal distribution)


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
# Warmup Iteration   1: 7.514 ops/ms
# Warmup Iteration   2: 11.950 ops/ms
# Warmup Iteration   3: 12.932 ops/ms
Iteration   1: 13.084 ops/ms
Iteration   2: 12.941 ops/ms
Iteration   3: 12.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.950 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (12.826, 12.950, 13.084), stdev = 0.129
  CI (99.9%): [10.596, 15.305] (assumes normal distribution)


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
# Warmup Iteration   1: 6.483 ops/ms
# Warmup Iteration   2: 10.395 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.602 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (10.496, 10.602, 10.701), stdev = 0.102
  CI (99.9%): [8.734, 12.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.550 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (2.497, 2.518, 2.550), stdev = 0.028
  CI (99.9%): [2.000, 3.035] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.003 ms/op
Iteration   2: 2.466 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.460, 2.467, 2.475), stdev = 0.008
  CI (99.9%): [2.324, 2.610] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.003 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.468, 2.485, 2.498), stdev = 0.015
  CI (99.9%): [2.204, 2.766] (assumes normal distribution)


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
Iteration   3: 2.948 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.947 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.944, 2.947, 2.950), stdev = 0.003
  CI (99.9%): [2.887, 3.008] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  12.523 ms/op
                 createUser·p0.9999: 16.176 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.823 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.866 ms/op
                 createUser·p0.9999: 10.289 ms/op
                 createUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380221
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 184179 
    [ 2.500,  3.750) = 190557 
    [ 3.750,  5.000) = 4086 
    [ 5.000,  6.250) = 824 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 153 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     14.696 ms/op
     p(99.9990) =     16.354 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  6.001 ms/op
                 existUser·p0.9999: 14.826 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.150 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 11.335 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392416
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 194424 
    [ 2.500,  3.750) = 194962 
    [ 3.750,  5.000) = 2249 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      6.013 ms/op
     p(99.9900) =     13.431 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.239 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  7.306 ms/op
                 getUser·p0.9999: 12.812 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.918 ms/op
                 getUser·p0.999:  7.721 ms/op
                 getUser·p0.9999: 15.139 ms/op
                 getUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389212
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 196430 
    [ 2.500,  3.750) = 187754 
    [ 3.750,  5.000) = 3819 
    [ 5.000,  6.250) = 657 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      7.393 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     15.830 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.246 ms/op
                 listUser·p0.9999: 10.819 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   2: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.430 ms/op
                 listUser·p0.9999: 11.114 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.487 ms/op
                 listUser·p0.999:  9.360 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321017
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 96729 
    [ 2.500,  3.750) = 187261 
    [ 3.750,  5.000) = 30011 
    [ 5.000,  6.250) = 5560 
    [ 6.250,  7.500) = 658 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.198 ms/op
     p(99.9990) =     13.060 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.464 ± 2.056  ops/ms
ClientPb.existUser                       thrpt       3  12.912 ± 1.609  ops/ms
ClientPb.getUser                         thrpt       3  12.950 ± 2.355  ops/ms
ClientPb.listUser                        thrpt       3  10.602 ± 1.867  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.518   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.143   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.281   ms/op
ClientPb.listUser                         avgt       3   2.947 ± 0.060   ms/op
ClientPb.createUser                     sample  380221   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.593           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.696           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.499           ms/op
ClientPb.existUser                      sample  392416   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.699           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.431           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  389212   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.698           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.393           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.336           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.909           ms/op
ClientPb.listUser                       sample  321017   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.783           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.198           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.156           ms/op
