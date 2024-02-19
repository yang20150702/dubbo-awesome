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
# Warmup Iteration   1: 5.072 ops/ms
# Warmup Iteration   2: 12.006 ops/ms
# Warmup Iteration   3: 12.216 ops/ms
Iteration   1: 12.606 ops/ms
Iteration   2: 12.401 ops/ms
Iteration   3: 12.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.347 ±(99.9%) 5.280 ops/ms [Average]
  (min, avg, max) = (12.035, 12.347, 12.606), stdev = 0.289
  CI (99.9%): [7.068, 17.627] (assumes normal distribution)


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
# Warmup Iteration   1: 8.139 ops/ms
# Warmup Iteration   2: 13.174 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 13.100 ops/ms
Iteration   2: 13.176 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.089 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (12.991, 13.089, 13.176), stdev = 0.093
  CI (99.9%): [11.394, 14.783] (assumes normal distribution)


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
# Warmup Iteration   1: 7.992 ops/ms
# Warmup Iteration   2: 12.626 ops/ms
# Warmup Iteration   3: 12.974 ops/ms
Iteration   1: 13.006 ops/ms
Iteration   2: 12.952 ops/ms
Iteration   3: 13.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.014 ±(99.9%) 1.225 ops/ms [Average]
  (min, avg, max) = (12.952, 13.014, 13.085), stdev = 0.067
  CI (99.9%): [11.790, 14.239] (assumes normal distribution)


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
# Warmup Iteration   1: 6.770 ops/ms
# Warmup Iteration   2: 10.542 ops/ms
# Warmup Iteration   3: 10.720 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.742 ±(99.9%) 0.628 ops/ms [Average]
  (min, avg, max) = (10.718, 10.742, 10.782), stdev = 0.034
  CI (99.9%): [10.114, 11.370] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.003 ms/op
Iteration   2: 2.489 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.486, 2.494, 2.508), stdev = 0.012
  CI (99.9%): [2.280, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (2.442, 2.462, 2.487), stdev = 0.023
  CI (99.9%): [2.040, 2.884] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.003 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.491, 2.511, 2.526), stdev = 0.018
  CI (99.9%): [2.179, 2.842] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
Iteration   2: 2.947 ±(99.9%) 0.004 ms/op
Iteration   3: 2.962 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.954 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.947, 2.954, 2.962), stdev = 0.008
  CI (99.9%): [2.809, 3.098] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  11.282 ms/op
                 createUser·p0.9999: 13.725 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   4.071 ms/op
                 createUser·p0.999:  9.648 ms/op
                 createUser·p0.9999: 12.740 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 10.645 ms/op
                 createUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382976
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 184480 
    [ 2.500,  3.750) = 194060 
    [ 3.750,  5.000) = 3514 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     14.077 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  5.574 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  6.404 ms/op
                 existUser·p0.9999: 12.009 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 12.584 ms/op
                 existUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389707
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 195251 
    [ 2.500,  3.750) = 189779 
    [ 3.750,  5.000) = 3559 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.480 ms/op
     p(99.9900) =     13.157 ms/op
     p(99.9990) =     14.157 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  5.382 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.031 ms/op
                 getUser·p0.9999: 12.749 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  7.385 ms/op
                 getUser·p0.9999: 11.583 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383154
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 191230 
    [ 2.500,  3.750) = 186443 
    [ 3.750,  5.000) = 4293 
    [ 5.000,  6.250) = 729 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.975 ms/op
     p(99.9000) =      6.226 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.830 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.792 ms/op
                 listUser·p0.9999: 12.205 ms/op
                 listUser·p1.00:   13.222 ms/op

Iteration   2: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.105 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.261 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320250
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 92633 
    [ 2.500,  3.750) = 189210 
    [ 3.750,  5.000) = 31348 
    [ 5.000,  6.250) = 5856 
    [ 6.250,  7.500) = 425 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     11.386 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.347 ± 5.280  ops/ms
ClientPb.existUser                       thrpt       3  13.089 ± 1.694  ops/ms
ClientPb.getUser                         thrpt       3  13.014 ± 1.225  ops/ms
ClientPb.listUser                        thrpt       3  10.742 ± 0.628  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.214   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.422   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.332   ms/op
ClientPb.listUser                         avgt       3   2.954 ± 0.145   ms/op
ClientPb.createUser                     sample  382976   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.916           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.684           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  389707   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.736           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.480           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.157           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  383154   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.857           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.975           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.226           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.991           ms/op
ClientPb.listUser                       sample  320250   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.756           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.386           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.222           ms/op
