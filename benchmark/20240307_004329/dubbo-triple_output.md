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
# Warmup Iteration   1: 4.882 ops/ms
# Warmup Iteration   2: 12.188 ops/ms
# Warmup Iteration   3: 12.670 ops/ms
Iteration   1: 12.624 ops/ms
Iteration   2: 12.772 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.724 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (12.624, 12.724, 12.778), stdev = 0.087
  CI (99.9%): [11.132, 14.316] (assumes normal distribution)


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
# Warmup Iteration   1: 8.438 ops/ms
# Warmup Iteration   2: 12.780 ops/ms
# Warmup Iteration   3: 13.164 ops/ms
Iteration   1: 13.142 ops/ms
Iteration   2: 13.263 ops/ms
Iteration   3: 13.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.176 ±(99.9%) 1.375 ops/ms [Average]
  (min, avg, max) = (13.124, 13.176, 13.263), stdev = 0.075
  CI (99.9%): [11.801, 14.552] (assumes normal distribution)


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
# Warmup Iteration   1: 7.796 ops/ms
# Warmup Iteration   2: 12.870 ops/ms
# Warmup Iteration   3: 13.119 ops/ms
Iteration   1: 13.121 ops/ms
Iteration   2: 13.124 ops/ms
Iteration   3: 13.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.239 ±(99.9%) 3.680 ops/ms [Average]
  (min, avg, max) = (13.121, 13.239, 13.472), stdev = 0.202
  CI (99.9%): [9.559, 16.919] (assumes normal distribution)


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
# Warmup Iteration   1: 6.759 ops/ms
# Warmup Iteration   2: 10.559 ops/ms
# Warmup Iteration   3: 10.577 ops/ms
Iteration   1: 10.570 ops/ms
Iteration   2: 10.630 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.615 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (10.570, 10.615, 10.644), stdev = 0.039
  CI (99.9%): [9.898, 11.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.003 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (2.435, 2.481, 2.509), stdev = 0.040
  CI (99.9%): [1.750, 3.213] (assumes normal distribution)


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.004 ms/op
Iteration   1: 2.399 ±(99.9%) 0.004 ms/op
Iteration   2: 2.406 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.408 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.399, 2.408, 2.420), stdev = 0.011
  CI (99.9%): [2.210, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.403 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.420 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.403, 2.420, 2.435), stdev = 0.016
  CI (99.9%): [2.131, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 4.817 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.005 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
Iteration   3: 2.966 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.966, 2.982, 2.993), stdev = 0.015
  CI (99.9%): [2.711, 3.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.453 ms/op
                 createUser·p0.9999: 18.263 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  8.301 ms/op
                 createUser·p0.9999: 13.016 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  9.358 ms/op
                 createUser·p0.9999: 11.257 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381615
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 185391 
    [ 2.500,  3.750) = 191617 
    [ 3.750,  5.000) = 3509 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      9.397 ms/op
     p(99.9900) =     13.891 ms/op
     p(99.9990) =     19.050 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.414 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 13.582 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  6.948 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  5.833 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397091
  mean =      2.415 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 198266 
    [ 2.500,  3.750) = 195296 
    [ 3.750,  5.000) = 2603 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.175 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.271 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.655 ms/op
                 getUser·p0.999:  8.339 ms/op
                 getUser·p0.9999: 13.778 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  10.429 ms/op
                 getUser·p0.9999: 13.320 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  5.546 ms/op
                 getUser·p0.9999: 9.928 ms/op
                 getUser·p1.00:   10.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388558
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 193241 
    [ 2.500,  3.750) = 190131 
    [ 3.750,  5.000) = 4051 
    [ 5.000,  6.250) = 566 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     13.358 ms/op
     p(99.9990) =     13.947 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.655 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 11.744 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.689 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.665 ms/op
                 listUser·p0.9999: 11.309 ms/op
                 listUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320259
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 94673 
    [ 2.500,  3.750) = 187032 
    [ 3.750,  5.000) = 31613 
    [ 5.000,  6.250) = 5562 
    [ 6.250,  7.500) = 527 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.417 ms/op
     p(99.9900) =     11.550 ms/op
     p(99.9990) =     12.580 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.724 ± 1.592  ops/ms
ClientPb.existUser                       thrpt       3  13.176 ± 1.375  ops/ms
ClientPb.getUser                         thrpt       3  13.239 ± 3.680  ops/ms
ClientPb.listUser                        thrpt       3  10.615 ± 0.717  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.731   ms/op
ClientPb.existUser                        avgt       3   2.408 ± 0.198   ms/op
ClientPb.getUser                          avgt       3   2.420 ± 0.289   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.271   ms/op
ClientPb.createUser                     sample  381615   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.782           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.397           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.891           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.202           ms/op
ClientPb.existUser                      sample  397091   2.415 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.175           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.565           ms/op
ClientPb.getUser                        sample  388558   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.258           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.358           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.074           ms/op
ClientPb.listUser                       sample  320259   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.689           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.550           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
