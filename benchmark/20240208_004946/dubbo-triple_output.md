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
# Warmup Iteration   1: 5.189 ops/ms
# Warmup Iteration   2: 12.209 ops/ms
# Warmup Iteration   3: 12.630 ops/ms
Iteration   1: 12.710 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.758 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (12.710, 12.758, 12.799), stdev = 0.045
  CI (99.9%): [11.941, 13.574] (assumes normal distribution)


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
# Warmup Iteration   1: 8.450 ops/ms
# Warmup Iteration   2: 13.343 ops/ms
# Warmup Iteration   3: 13.223 ops/ms
Iteration   1: 13.027 ops/ms
Iteration   2: 13.244 ops/ms
Iteration   3: 13.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.182 ±(99.9%) 2.464 ops/ms [Average]
  (min, avg, max) = (13.027, 13.182, 13.275), stdev = 0.135
  CI (99.9%): [10.718, 15.646] (assumes normal distribution)


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
# Warmup Iteration   1: 8.085 ops/ms
# Warmup Iteration   2: 12.802 ops/ms
# Warmup Iteration   3: 13.229 ops/ms
Iteration   1: 13.042 ops/ms
Iteration   2: 13.025 ops/ms
Iteration   3: 12.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.008 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (12.958, 13.008, 13.042), stdev = 0.045
  CI (99.9%): [12.195, 13.822] (assumes normal distribution)


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
# Warmup Iteration   1: 6.639 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.529 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.630 ±(99.9%) 0.239 ops/ms [Average]
  (min, avg, max) = (10.618, 10.630, 10.644), stdev = 0.013
  CI (99.9%): [10.391, 10.868] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.844 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.478 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.457, 2.478, 2.499), stdev = 0.021
  CI (99.9%): [2.093, 2.863] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.409 ±(99.9%) 0.003 ms/op
Iteration   3: 2.426 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.409, 2.422, 2.429), stdev = 0.011
  CI (99.9%): [2.226, 2.617] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.003 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.472 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (2.443, 2.472, 2.513), stdev = 0.037
  CI (99.9%): [1.805, 3.139] (assumes normal distribution)


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
Iteration   2: 3.004 ±(99.9%) 0.004 ms/op
Iteration   3: 3.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.991, 3.004, 3.017), stdev = 0.013
  CI (99.9%): [2.767, 3.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.840 ms/op
                 createUser·p0.9999: 15.651 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  10.031 ms/op
                 createUser·p0.9999: 12.512 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 15.712 ms/op
                 createUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382159
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 184212 
    [ 2.500,  3.750) = 194374 
    [ 3.750,  5.000) = 2776 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      9.146 ms/op
     p(99.9900) =     15.538 ms/op
     p(99.9990) =     15.846 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  7.193 ms/op
                 existUser·p0.9999: 13.259 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 13.024 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  6.926 ms/op
                 existUser·p0.9999: 11.468 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389774
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 192637 
    [ 2.500,  3.750) = 194214 
    [ 3.750,  5.000) = 2123 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.422 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 14.235 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  9.821 ms/op
                 getUser·p0.9999: 14.438 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  7.754 ms/op
                 getUser·p0.9999: 12.357 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382912
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 189705 
    [ 2.500,  3.750) = 188573 
    [ 3.750,  5.000) = 3421 
    [ 5.000,  6.250) = 682 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.878 ms/op
     p(99.9000) =      7.955 ms/op
     p(99.9900) =     13.971 ms/op
     p(99.9990) =     14.653 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.810 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.009 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.107 ms/op
                 listUser·p0.9999: 11.973 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.497 ms/op
                 listUser·p0.9999: 11.438 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.574 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313152
  mean =      3.063 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 82836 
    [ 2.500,  3.750) = 187091 
    [ 3.750,  5.000) = 35007 
    [ 5.000,  6.250) = 6549 
    [ 6.250,  7.500) = 804 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 329 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.532 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.758 ± 0.816  ops/ms
ClientPb.existUser                       thrpt       3  13.182 ± 2.464  ops/ms
ClientPb.getUser                         thrpt       3  13.008 ± 0.813  ops/ms
ClientPb.listUser                        thrpt       3  10.630 ± 0.239  ops/ms
ClientPb.createUser                       avgt       3   2.478 ± 0.385   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.196   ms/op
ClientPb.getUser                          avgt       3   2.472 ± 0.667   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.237   ms/op
ClientPb.createUser                     sample  382159   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.146           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.538           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.942           ms/op
ClientPb.existUser                      sample  389774   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.730           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  382912   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.608           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.878           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.955           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.971           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  313152   3.063 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.740           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.648           ms/op
