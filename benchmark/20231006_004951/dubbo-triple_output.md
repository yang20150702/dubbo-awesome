# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 4.604 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 8.829 ops/ms
Iteration   2: 9.173 ops/ms
Iteration   3: 9.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.098 ±(99.9%) 4.376 ops/ms [Average]
  (min, avg, max) = (8.829, 9.098, 9.291), stdev = 0.240
  CI (99.9%): [4.721, 13.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 9.376 ops/ms
Iteration   2: 9.422 ops/ms
Iteration   3: 9.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.366 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (9.300, 9.366, 9.422), stdev = 0.062
  CI (99.9%): [8.242, 10.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 8.465 ops/ms
# Warmup Iteration   3: 8.645 ops/ms
Iteration   1: 8.835 ops/ms
Iteration   2: 9.167 ops/ms
Iteration   3: 8.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.962 ±(99.9%) 3.280 ops/ms [Average]
  (min, avg, max) = (8.835, 8.962, 9.167), stdev = 0.180
  CI (99.9%): [5.682, 12.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.955 ops/ms
# Warmup Iteration   2: 7.126 ops/ms
# Warmup Iteration   3: 7.523 ops/ms
Iteration   1: 7.610 ops/ms
Iteration   2: 7.585 ops/ms
Iteration   3: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.592 ±(99.9%) 0.293 ops/ms [Average]
  (min, avg, max) = (7.580, 7.592, 7.610), stdev = 0.016
  CI (99.9%): [7.299, 7.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.831 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.006 ms/op
Iteration   1: 3.679 ±(99.9%) 0.005 ms/op
Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
Iteration   3: 3.599 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.650 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.599, 3.650, 3.679), stdev = 0.044
  CI (99.9%): [2.847, 4.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.388 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.005 ms/op
Iteration   1: 3.474 ±(99.9%) 0.003 ms/op
Iteration   2: 3.518 ±(99.9%) 0.003 ms/op
Iteration   3: 3.356 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.450 ±(99.9%) 1.523 ms/op [Average]
  (min, avg, max) = (3.356, 3.450, 3.518), stdev = 0.083
  CI (99.9%): [1.927, 4.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.506 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.004 ms/op
Iteration   1: 3.514 ±(99.9%) 0.007 ms/op
Iteration   2: 3.602 ±(99.9%) 0.005 ms/op
Iteration   3: 3.442 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.520 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.442, 3.520, 3.602), stdev = 0.080
  CI (99.9%): [2.057, 4.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.258 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.004 ms/op
Iteration   1: 4.175 ±(99.9%) 0.003 ms/op
Iteration   2: 4.160 ±(99.9%) 0.006 ms/op
Iteration   3: 4.212 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.182 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (4.160, 4.182, 4.212), stdev = 0.027
  CI (99.9%): [3.695, 4.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.941 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.011 ms/op
Iteration   1: 3.559 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 28.508 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 3.598 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  20.228 ms/op
                 createUser·p0.9999: 23.834 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.587 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  16.837 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268046
  mean =      3.581 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3705 
    [ 2.500,  5.000) = 254342 
    [ 5.000,  7.500) = 7825 
    [ 7.500, 10.000) = 1425 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     28.650 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.120 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.012 ms/op
Iteration   1: 3.405 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  13.009 ms/op
                 existUser·p0.9999: 22.695 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.510 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.864 ms/op
                 existUser·p0.999:  21.771 ms/op
                 existUser·p0.9999: 41.091 ms/op
                 existUser·p1.00:   44.761 ms/op

Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  18.933 ms/op
                 existUser·p0.9999: 26.101 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279702
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 272558 
    [ 5.000, 10.000) = 6394 
    [10.000, 15.000) = 429 
    [15.000, 20.000) = 80 
    [20.000, 25.000) = 173 
    [25.000, 30.000) = 36 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     40.044 ms/op
     p(99.9990) =     42.680 ms/op
     p(99.9999) =     44.761 ms/op
    p(100.0000) =     44.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.128 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.012 ms/op
Iteration   1: 3.688 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.554 ms/op
                 getUser·p0.999:  16.192 ms/op
                 getUser·p0.9999: 23.495 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.536 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.623 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  20.328 ms/op
                 getUser·p0.9999: 25.537 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265417
  mean =      3.615 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3136 
    [ 2.500,  5.000) = 251504 
    [ 5.000,  7.500) = 8694 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     18.593 ms/op
     p(99.9900) =     24.132 ms/op
     p(99.9990) =     25.768 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.340 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.014 ms/op
Iteration   1: 4.234 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  20.290 ms/op
                 listUser·p0.9999: 24.212 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   2: 4.216 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 17.589 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 4.236 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  14.878 ms/op
                 listUser·p0.9999: 18.267 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226862
  mean =      4.229 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 133 
    [ 2.500,  5.000) = 213160 
    [ 5.000,  7.500) = 9249 
    [ 7.500, 10.000) = 3238 
    [10.000, 12.500) = 490 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.818 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.098 ± 4.376  ops/ms
ClientPb.existUser                       thrpt       3   9.366 ± 1.124  ops/ms
ClientPb.getUser                         thrpt       3   8.962 ± 3.280  ops/ms
ClientPb.listUser                        thrpt       3   7.592 ± 0.293  ops/ms
ClientPb.createUser                       avgt       3   3.650 ± 0.803   ms/op
ClientPb.existUser                        avgt       3   3.450 ± 1.523   ms/op
ClientPb.getUser                          avgt       3   3.520 ± 1.463   ms/op
ClientPb.listUser                         avgt       3   4.182 ± 0.488   ms/op
ClientPb.createUser                     sample  268046   3.581 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.805           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.738           ms/op
ClientPb.existUser                      sample  279702   3.433 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.612           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.044           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.761           ms/op
ClientPb.getUser                        sample  265417   3.615 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.165           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.593           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.132           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.919           ms/op
ClientPb.listUser                       sample  226862   4.229 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.969           ms/op
