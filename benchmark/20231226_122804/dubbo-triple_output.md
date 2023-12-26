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
# Warmup Iteration   1: 5.320 ops/ms
# Warmup Iteration   2: 12.297 ops/ms
# Warmup Iteration   3: 12.594 ops/ms
Iteration   1: 12.714 ops/ms
Iteration   2: 12.738 ops/ms
Iteration   3: 12.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.779 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (12.714, 12.779, 12.884), stdev = 0.092
  CI (99.9%): [11.105, 14.453] (assumes normal distribution)


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
# Warmup Iteration   1: 8.429 ops/ms
# Warmup Iteration   2: 13.035 ops/ms
# Warmup Iteration   3: 13.286 ops/ms
Iteration   1: 13.079 ops/ms
Iteration   2: 13.067 ops/ms
Iteration   3: 13.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.166 ±(99.9%) 2.946 ops/ms [Average]
  (min, avg, max) = (13.067, 13.166, 13.352), stdev = 0.161
  CI (99.9%): [10.220, 16.112] (assumes normal distribution)


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
# Warmup Iteration   1: 7.748 ops/ms
# Warmup Iteration   2: 12.477 ops/ms
# Warmup Iteration   3: 12.778 ops/ms
Iteration   1: 12.786 ops/ms
Iteration   2: 12.795 ops/ms
Iteration   3: 12.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.836 ±(99.9%) 1.451 ops/ms [Average]
  (min, avg, max) = (12.786, 12.836, 12.928), stdev = 0.080
  CI (99.9%): [11.385, 14.287] (assumes normal distribution)


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
# Warmup Iteration   1: 6.589 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.592 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (10.572, 10.592, 10.629), stdev = 0.032
  CI (99.9%): [10.001, 11.183] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
Iteration   3: 2.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (2.540, 2.544, 2.551), stdev = 0.006
  CI (99.9%): [2.440, 2.648] (assumes normal distribution)


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.004 ms/op
Iteration   2: 2.407 ±(99.9%) 0.003 ms/op
Iteration   3: 2.430 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.407, 2.424, 2.436), stdev = 0.016
  CI (99.9%): [2.138, 2.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.438 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (2.417, 2.438, 2.473), stdev = 0.031
  CI (99.9%): [1.879, 2.998] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.634 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 2.999 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.998 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.995, 2.998, 3.000), stdev = 0.003
  CI (99.9%): [2.945, 3.051] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  10.333 ms/op
                 createUser·p0.9999: 14.467 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  9.316 ms/op
                 createUser·p0.9999: 15.016 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  7.839 ms/op
                 createUser·p0.9999: 11.139 ms/op
                 createUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381304
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 183642 
    [ 2.500,  3.750) = 194383 
    [ 3.750,  5.000) = 2510 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.859 ms/op
     p(99.9900) =     14.512 ms/op
     p(99.9990) =     15.606 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  5.493 ms/op
                 existUser·p0.9999: 13.475 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.810 ms/op
                 existUser·p0.999:  8.281 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  9.183 ms/op
                 existUser·p0.9999: 11.905 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397432
  mean =      2.413 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 200052 
    [ 2.500,  3.750) = 194260 
    [ 3.750,  5.000) = 2176 
    [ 5.000,  6.250) = 317 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 147 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     13.062 ms/op
     p(99.9990) =     13.911 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  6.839 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 12.517 ms/op
                 getUser·p1.00:   13.222 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.335 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  7.138 ms/op
                 getUser·p0.9999: 11.309 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386201
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 192981 
    [ 2.500,  3.750) = 188158 
    [ 3.750,  5.000) = 3833 
    [ 5.000,  6.250) = 549 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.500 ms/op
     p(99.9900) =     13.228 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.644 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.384 ms/op
                 listUser·p0.9999: 12.278 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.512 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.279 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.351 ms/op
                 listUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318520
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 91624 
    [ 2.500,  3.750) = 187269 
    [ 3.750,  5.000) = 32512 
    [ 5.000,  6.250) = 5810 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.497 ms/op
     p(99.9990) =     12.449 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.779 ± 1.674  ops/ms
ClientPb.existUser                       thrpt       3  13.166 ± 2.946  ops/ms
ClientPb.getUser                         thrpt       3  12.836 ± 1.451  ops/ms
ClientPb.listUser                        thrpt       3  10.592 ± 0.591  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.104   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.286   ms/op
ClientPb.getUser                          avgt       3   2.438 ± 0.559   ms/op
ClientPb.listUser                         avgt       3   2.998 ± 0.053   ms/op
ClientPb.createUser                     sample  381304   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.859           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.512           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.761           ms/op
ClientPb.existUser                      sample  397432   2.413 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.940           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.011           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.062           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  386201   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.500           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.228           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.779           ms/op
ClientPb.listUser                       sample  318520   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.644           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.497           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
