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
# Warmup Iteration   1: 5.243 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.563 ops/ms
Iteration   1: 12.773 ops/ms
Iteration   2: 12.714 ops/ms
Iteration   3: 12.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.782 ±(99.9%) 1.324 ops/ms [Average]
  (min, avg, max) = (12.714, 12.782, 12.859), stdev = 0.073
  CI (99.9%): [11.458, 14.106] (assumes normal distribution)


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
# Warmup Iteration   1: 8.168 ops/ms
# Warmup Iteration   2: 13.245 ops/ms
# Warmup Iteration   3: 13.440 ops/ms
Iteration   1: 13.290 ops/ms
Iteration   2: 13.292 ops/ms
Iteration   3: 13.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.288 ±(99.9%) 0.092 ops/ms [Average]
  (min, avg, max) = (13.282, 13.288, 13.292), stdev = 0.005
  CI (99.9%): [13.196, 13.380] (assumes normal distribution)


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
# Warmup Iteration   1: 7.744 ops/ms
# Warmup Iteration   2: 12.649 ops/ms
# Warmup Iteration   3: 12.688 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.763 ops/ms
Iteration   3: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.777 ±(99.9%) 0.496 ops/ms [Average]
  (min, avg, max) = (12.761, 12.777, 12.809), stdev = 0.027
  CI (99.9%): [12.281, 13.274] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.963 ops/ms
# Warmup Iteration   2: 10.687 ops/ms
# Warmup Iteration   3: 10.856 ops/ms
Iteration   1: 10.816 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.845 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (10.816, 10.845, 10.904), stdev = 0.051
  CI (99.9%): [9.924, 11.767] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.479, 2.495, 2.516), stdev = 0.019
  CI (99.9%): [2.149, 2.841] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.004 ms/op
Iteration   1: 2.419 ±(99.9%) 0.004 ms/op
Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
Iteration   3: 2.402 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.415 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.402, 2.415, 2.424), stdev = 0.011
  CI (99.9%): [2.206, 2.624] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.003 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.459 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.449, 2.454, 2.459), stdev = 0.005
  CI (99.9%): [2.364, 2.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
Iteration   3: 2.991 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.990 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.983, 2.990, 2.998), stdev = 0.007
  CI (99.9%): [2.854, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 13.931 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.915 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 12.456 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  8.175 ms/op
                 createUser·p0.9999: 11.174 ms/op
                 createUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382425
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 183658 
    [ 2.500,  3.750) = 193691 
    [ 3.750,  5.000) = 4088 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.310 ms/op
     p(99.9900) =     13.136 ms/op
     p(99.9990) =     14.020 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.006 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.909 ms/op
                 existUser·p0.999:  7.458 ms/op
                 existUser·p0.9999: 14.920 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   2: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 13.983 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  6.771 ms/op
                 existUser·p0.9999: 11.706 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396039
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 200024 
    [ 2.500,  3.750) = 191447 
    [ 3.750,  5.000) = 3662 
    [ 5.000,  6.250) = 368 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     14.264 ms/op
     p(99.9990) =     15.393 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  10.447 ms/op
                 getUser·p0.9999: 14.945 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.411 ms/op
                 getUser·p0.9999: 12.879 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  8.485 ms/op
                 getUser·p0.9999: 11.616 ms/op
                 getUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378685
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 185660 
    [ 2.500,  3.750) = 187596 
    [ 3.750,  5.000) = 4388 
    [ 5.000,  6.250) = 539 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      6.608 ms/op
     p(99.9900) =     13.832 ms/op
     p(99.9990) =     15.600 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.961 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.755 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.396 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.720 ms/op
                 listUser·p0.9999: 11.191 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314474
  mean =      3.050 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 86027 
    [ 2.500,  3.750) = 186345 
    [ 3.750,  5.000) = 34102 
    [ 5.000,  6.250) = 6435 
    [ 6.250,  7.500) = 694 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 330 
    [10.000, 11.250) = 203 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.223 ms/op
     p(99.9990) =     11.565 ms/op
     p(99.9999) =     11.649 ms/op
    p(100.0000) =     11.649 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.782 ± 1.324  ops/ms
ClientPb.existUser                       thrpt       3  13.288 ± 0.092  ops/ms
ClientPb.getUser                         thrpt       3  12.777 ± 0.496  ops/ms
ClientPb.listUser                        thrpt       3  10.845 ± 0.922  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.346   ms/op
ClientPb.existUser                        avgt       3   2.415 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.090   ms/op
ClientPb.listUser                         avgt       3   2.990 ± 0.137   ms/op
ClientPb.createUser                     sample  382425   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.830           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.310           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.136           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  396039   2.422 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.664           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.734           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.264           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.663           ms/op
ClientPb.getUser                        sample  378685   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.608           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.832           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.007           ms/op
ClientPb.listUser                       sample  314474   3.050 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.736           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.223           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.649           ms/op
