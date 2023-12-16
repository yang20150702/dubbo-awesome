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
# Warmup Iteration   1: 5.236 ops/ms
# Warmup Iteration   2: 12.274 ops/ms
# Warmup Iteration   3: 12.318 ops/ms
Iteration   1: 12.685 ops/ms
Iteration   2: 12.753 ops/ms
Iteration   3: 12.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.686 ±(99.9%) 1.229 ops/ms [Average]
  (min, avg, max) = (12.618, 12.686, 12.753), stdev = 0.067
  CI (99.9%): [11.456, 13.915] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.878 ops/ms
# Warmup Iteration   2: 12.772 ops/ms
# Warmup Iteration   3: 12.871 ops/ms
Iteration   1: 13.013 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.952 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (12.833, 12.952, 13.013), stdev = 0.103
  CI (99.9%): [11.076, 14.828] (assumes normal distribution)


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
# Warmup Iteration   1: 7.757 ops/ms
# Warmup Iteration   2: 12.574 ops/ms
# Warmup Iteration   3: 12.757 ops/ms
Iteration   1: 12.995 ops/ms
Iteration   2: 12.727 ops/ms
Iteration   3: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.839 ±(99.9%) 2.536 ops/ms [Average]
  (min, avg, max) = (12.727, 12.839, 12.995), stdev = 0.139
  CI (99.9%): [10.303, 15.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.652 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.751 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.764 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (10.733, 10.764, 10.794), stdev = 0.030
  CI (99.9%): [10.208, 11.320] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.513, 2.522, 2.528), stdev = 0.008
  CI (99.9%): [2.379, 2.665] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.415 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.427 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.412, 2.418, 2.427), stdev = 0.008
  CI (99.9%): [2.271, 2.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.483, 2.494, 2.506), stdev = 0.011
  CI (99.9%): [2.287, 2.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.004 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
Iteration   3: 3.020 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.000, 3.018, 3.035), stdev = 0.017
  CI (99.9%): [2.699, 3.337] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  11.117 ms/op
                 createUser·p0.9999: 14.092 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  10.025 ms/op
                 createUser·p0.9999: 11.822 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 11.928 ms/op
                 createUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379901
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 184020 
    [ 2.500,  3.750) = 192249 
    [ 3.750,  5.000) = 2987 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      9.422 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.965 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.256 ms/op
                 existUser·p0.9999: 15.217 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.464 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.332 ms/op
                 existUser·p0.9999: 12.469 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.460 ms/op
                 existUser·p0.9999: 11.268 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394886
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 198203 
    [ 2.500,  3.750) = 193604 
    [ 3.750,  5.000) = 2254 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.984 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     15.942 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  8.318 ms/op
                 getUser·p0.9999: 16.141 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  6.029 ms/op
                 getUser·p0.9999: 12.294 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  8.368 ms/op
                 getUser·p0.9999: 13.024 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381926
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 188997 
    [ 2.500,  3.750) = 188245 
    [ 3.750,  5.000) = 3844 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.849 ms/op
     p(99.9000) =      6.730 ms/op
     p(99.9900) =     14.398 ms/op
     p(99.9990) =     17.399 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.758 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  9.458 ms/op
                 listUser·p0.9999: 14.348 ms/op
                 listUser·p1.00:   15.729 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 11.088 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.108 ms/op
                 listUser·p0.9999: 11.246 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318158
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 92922 
    [ 2.500,  3.750) = 185383 
    [ 3.750,  5.000) = 31960 
    [ 5.000,  6.250) = 6394 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     12.680 ms/op
     p(99.9990) =     15.462 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.686 ± 1.229  ops/ms
ClientPb.existUser                       thrpt       3  12.952 ± 1.876  ops/ms
ClientPb.getUser                         thrpt       3  12.839 ± 2.536  ops/ms
ClientPb.listUser                        thrpt       3  10.764 ± 0.556  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.143   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.146   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.207   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.319   ms/op
ClientPb.createUser                     sample  379901   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.422           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.140           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.090           ms/op
ClientPb.existUser                      sample  394886   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.464           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.984           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.286           ms/op
ClientPb.getUser                        sample  381926   2.511 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.801           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.849           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.398           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.957           ms/op
ClientPb.listUser                       sample  318158   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.680           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.729           ms/op
