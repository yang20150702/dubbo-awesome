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
# Warmup Iteration   1: 4.656 ops/ms
# Warmup Iteration   2: 11.785 ops/ms
# Warmup Iteration   3: 12.382 ops/ms
Iteration   1: 12.401 ops/ms
Iteration   2: 12.367 ops/ms
Iteration   3: 12.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.394 ±(99.9%) 0.439 ops/ms [Average]
  (min, avg, max) = (12.367, 12.394, 12.413), stdev = 0.024
  CI (99.9%): [11.955, 12.833] (assumes normal distribution)


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
# Warmup Iteration   1: 7.363 ops/ms
# Warmup Iteration   2: 12.575 ops/ms
# Warmup Iteration   3: 12.610 ops/ms
Iteration   1: 12.526 ops/ms
Iteration   2: 12.772 ops/ms
Iteration   3: 12.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.677 ±(99.9%) 2.406 ops/ms [Average]
  (min, avg, max) = (12.526, 12.677, 12.772), stdev = 0.132
  CI (99.9%): [10.270, 15.083] (assumes normal distribution)


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
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 12.370 ops/ms
# Warmup Iteration   3: 12.562 ops/ms
Iteration   1: 12.592 ops/ms
Iteration   2: 12.590 ops/ms
Iteration   3: 12.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.599 ±(99.9%) 0.256 ops/ms [Average]
  (min, avg, max) = (12.590, 12.599, 12.616), stdev = 0.014
  CI (99.9%): [12.344, 12.855] (assumes normal distribution)


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
# Warmup Iteration   1: 6.622 ops/ms
# Warmup Iteration   2: 10.275 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.439 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (10.385, 10.439, 10.478), stdev = 0.048
  CI (99.9%): [9.555, 11.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.555 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.541, 2.555, 2.577), stdev = 0.019
  CI (99.9%): [2.200, 2.911] (assumes normal distribution)


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.462, 2.475, 2.485), stdev = 0.012
  CI (99.9%): [2.253, 2.697] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.527 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.518, 2.527, 2.537), stdev = 0.009
  CI (99.9%): [2.355, 2.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.006 ms/op
Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
Iteration   3: 3.078 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.086 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (3.072, 3.086, 3.108), stdev = 0.019
  CI (99.9%): [2.734, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.554 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  12.433 ms/op
                 createUser·p0.9999: 20.545 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  10.338 ms/op
                 createUser·p0.9999: 14.098 ms/op
                 createUser·p1.00:   17.826 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.670 ms/op
                 createUser·p0.9999: 10.830 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380272
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181065 
    [ 2.500,  5.000) = 196512 
    [ 5.000,  7.500) = 2214 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     14.826 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  6.535 ms/op
                 existUser·p0.9999: 14.156 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  8.288 ms/op
                 existUser·p0.9999: 12.506 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  7.195 ms/op
                 existUser·p0.9999: 10.463 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387730
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 188873 
    [ 2.500,  3.750) = 194741 
    [ 3.750,  5.000) = 3209 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.783 ms/op
     p(99.9000) =      7.216 ms/op
     p(99.9900) =     13.541 ms/op
     p(99.9990) =     14.256 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  12.187 ms/op
                 getUser·p0.9999: 15.014 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  9.687 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  7.414 ms/op
                 getUser·p0.9999: 12.749 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380836
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 187100 
    [ 2.500,  3.750) = 188188 
    [ 3.750,  5.000) = 4373 
    [ 5.000,  6.250) = 666 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      7.749 ms/op
     p(99.9900) =     14.399 ms/op
     p(99.9990) =     15.676 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 10.600 ms/op
                 listUser·p1.00:   10.879 ms/op

Iteration   2: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.158 ms/op
                 listUser·p0.9999: 12.468 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.655 ms/op
                 listUser·p0.999:  9.996 ms/op
                 listUser·p0.9999: 11.625 ms/op
                 listUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314734
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 86457 
    [ 2.500,  3.750) = 186128 
    [ 3.750,  5.000) = 34418 
    [ 5.000,  6.250) = 6319 
    [ 6.250,  7.500) = 659 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 228 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     13.198 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.394 ± 0.439  ops/ms
ClientPb.existUser                       thrpt       3  12.677 ± 2.406  ops/ms
ClientPb.getUser                         thrpt       3  12.599 ± 0.256  ops/ms
ClientPb.listUser                        thrpt       3  10.439 ± 0.884  ops/ms
ClientPb.createUser                       avgt       3   2.555 ± 0.355   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.222   ms/op
ClientPb.getUser                          avgt       3   2.527 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   3.086 ± 0.352   ms/op
ClientPb.createUser                     sample  380272   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.815           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.826           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.921           ms/op
ClientPb.existUser                      sample  387730   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.828           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.783           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.216           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.541           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  380836   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.825           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.749           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.745           ms/op
ClientPb.listUser                       sample  314734   3.047 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.857           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.863           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.878           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
