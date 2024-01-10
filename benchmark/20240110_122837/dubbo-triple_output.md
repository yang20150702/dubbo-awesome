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
# Warmup Iteration   1: 4.622 ops/ms
# Warmup Iteration   2: 12.202 ops/ms
# Warmup Iteration   3: 12.448 ops/ms
Iteration   1: 12.626 ops/ms
Iteration   2: 12.552 ops/ms
Iteration   3: 12.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.627 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (12.552, 12.627, 12.703), stdev = 0.075
  CI (99.9%): [11.258, 13.996] (assumes normal distribution)


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
# Warmup Iteration   1: 8.055 ops/ms
# Warmup Iteration   2: 12.854 ops/ms
# Warmup Iteration   3: 13.054 ops/ms
Iteration   1: 13.110 ops/ms
Iteration   2: 13.106 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.069 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (12.991, 13.069, 13.110), stdev = 0.067
  CI (99.9%): [11.840, 14.299] (assumes normal distribution)


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
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 12.409 ops/ms
# Warmup Iteration   3: 12.915 ops/ms
Iteration   1: 12.894 ops/ms
Iteration   2: 12.851 ops/ms
Iteration   3: 12.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.890 ±(99.9%) 0.687 ops/ms [Average]
  (min, avg, max) = (12.851, 12.890, 12.926), stdev = 0.038
  CI (99.9%): [12.203, 13.578] (assumes normal distribution)


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
# Warmup Iteration   1: 6.641 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.677 ops/ms
Iteration   2: 10.652 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.629 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (10.558, 10.629, 10.677), stdev = 0.063
  CI (99.9%): [9.479, 11.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
Iteration   1: 2.608 ±(99.9%) 0.003 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (2.549, 2.569, 2.608), stdev = 0.034
  CI (99.9%): [1.947, 3.191] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.461, 2.473, 2.481), stdev = 0.010
  CI (99.9%): [2.291, 2.654] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.525 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.514, 2.525, 2.536), stdev = 0.011
  CI (99.9%): [2.330, 2.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.957, 2.968, 2.977), stdev = 0.010
  CI (99.9%): [2.787, 3.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.675 ms/op
                 createUser·p0.999:  9.479 ms/op
                 createUser·p0.9999: 14.592 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  8.816 ms/op
                 createUser·p0.9999: 11.965 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.725 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 10.513 ms/op
                 createUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383943
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 185585 
    [ 2.500,  3.750) = 194399 
    [ 3.750,  5.000) = 2935 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.438 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.268 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.465 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  8.230 ms/op
                 existUser·p0.9999: 18.875 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.611 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 11.272 ms/op
                 existUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390840
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 194851 
    [ 2.500,  3.750) = 193259 
    [ 3.750,  5.000) = 1976 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      6.660 ms/op
     p(99.9900) =     15.844 ms/op
     p(99.9990) =     19.738 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  7.537 ms/op
                 getUser·p0.9999: 13.456 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.745 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 12.575 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.750 ms/op
                 getUser·p0.999:  6.849 ms/op
                 getUser·p0.9999: 10.576 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385365
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 191864 
    [ 2.500,  3.750) = 188848 
    [ 3.750,  5.000) = 3096 
    [ 5.000,  6.250) = 1078 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      7.530 ms/op
     p(99.9900) =     13.073 ms/op
     p(99.9990) =     14.430 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.009 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.830 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.396 ms/op
                 listUser·p0.9999: 11.299 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.902 ms/op
                 listUser·p0.9999: 11.835 ms/op
                 listUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320012
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 93225 
    [ 2.500,  3.750) = 189453 
    [ 3.750,  5.000) = 30599 
    [ 5.000,  6.250) = 5281 
    [ 6.250,  7.500) = 684 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 214 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     12.268 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.627 ± 1.369  ops/ms
ClientPb.existUser                       thrpt       3  13.069 ± 1.230  ops/ms
ClientPb.getUser                         thrpt       3  12.890 ± 0.687  ops/ms
ClientPb.listUser                        thrpt       3  10.629 ± 1.150  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.622   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.182   ms/op
ClientPb.getUser                          avgt       3   2.525 ± 0.196   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.181   ms/op
ClientPb.createUser                     sample  383943   2.498 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.438           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.270           ms/op
ClientPb.existUser                      sample  390840   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.660           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.923           ms/op
ClientPb.getUser                        sample  385365   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.530           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.073           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  320012   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.320           ms/op
