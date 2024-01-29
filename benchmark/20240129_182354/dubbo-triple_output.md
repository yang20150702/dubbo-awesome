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
# Warmup Iteration   1: 4.832 ops/ms
# Warmup Iteration   2: 11.769 ops/ms
# Warmup Iteration   3: 12.163 ops/ms
Iteration   1: 12.439 ops/ms
Iteration   2: 12.580 ops/ms
Iteration   3: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.521 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (12.439, 12.521, 12.580), stdev = 0.073
  CI (99.9%): [11.187, 13.854] (assumes normal distribution)


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
# Warmup Iteration   1: 8.264 ops/ms
# Warmup Iteration   2: 12.631 ops/ms
# Warmup Iteration   3: 12.533 ops/ms
Iteration   1: 12.861 ops/ms
Iteration   2: 12.887 ops/ms
Iteration   3: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.865 ±(99.9%) 0.357 ops/ms [Average]
  (min, avg, max) = (12.848, 12.865, 12.887), stdev = 0.020
  CI (99.9%): [12.509, 13.222] (assumes normal distribution)


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
# Warmup Iteration   1: 7.859 ops/ms
# Warmup Iteration   2: 12.237 ops/ms
# Warmup Iteration   3: 12.492 ops/ms
Iteration   1: 12.625 ops/ms
Iteration   2: 12.651 ops/ms
Iteration   3: 12.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.670 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (12.625, 12.670, 12.734), stdev = 0.057
  CI (99.9%): [11.631, 13.710] (assumes normal distribution)


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
# Warmup Iteration   1: 6.596 ops/ms
# Warmup Iteration   2: 10.464 ops/ms
# Warmup Iteration   3: 10.579 ops/ms
Iteration   1: 10.593 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.541 ±(99.9%) 0.858 ops/ms [Average]
  (min, avg, max) = (10.501, 10.541, 10.593), stdev = 0.047
  CI (99.9%): [9.683, 11.399] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.003 ms/op
Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.522, 2.539, 2.561), stdev = 0.020
  CI (99.9%): [2.180, 2.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.474, 2.483, 2.491), stdev = 0.009
  CI (99.9%): [2.327, 2.640] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.003 ms/op
Iteration   3: 2.567 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.549 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.535, 2.549, 2.567), stdev = 0.016
  CI (99.9%): [2.256, 2.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
Iteration   3: 3.080 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.056 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.043, 3.056, 3.080), stdev = 0.020
  CI (99.9%): [2.688, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.672 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  11.502 ms/op
                 createUser·p0.9999: 14.671 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 14.900 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  9.019 ms/op
                 createUser·p0.9999: 11.674 ms/op
                 createUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376078
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 177884 
    [ 2.500,  3.750) = 193919 
    [ 3.750,  5.000) = 3281 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      9.108 ms/op
     p(99.9900) =     14.396 ms/op
     p(99.9990) =     15.405 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  7.264 ms/op
                 existUser·p0.9999: 15.323 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  6.300 ms/op
                 existUser·p0.9999: 13.355 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  7.252 ms/op
                 existUser·p0.9999: 11.848 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386597
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 189264 
    [ 2.500,  3.750) = 193798 
    [ 3.750,  5.000) = 2742 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      6.893 ms/op
     p(99.9900) =     13.708 ms/op
     p(99.9990) =     15.831 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  11.548 ms/op
                 getUser·p0.9999: 14.228 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  9.095 ms/op
                 getUser·p0.9999: 13.793 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  7.733 ms/op
                 getUser·p0.9999: 11.364 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378757
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 185261 
    [ 2.500,  3.750) = 188474 
    [ 3.750,  5.000) = 4074 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.897 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.441 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.722 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.009 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.002 ms/op
                 listUser·p1.00:   11.207 ms/op

Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.502 ms/op
                 listUser·p0.9999: 12.698 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.568 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.635 ms/op
                 listUser·p0.999:  9.709 ms/op
                 listUser·p0.9999: 12.325 ms/op
                 listUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315837
  mean =      3.036 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 89724 
    [ 2.500,  3.750) = 184800 
    [ 3.750,  5.000) = 32941 
    [ 5.000,  6.250) = 6544 
    [ 6.250,  7.500) = 843 
    [ 7.500,  8.750) = 342 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     11.955 ms/op
     p(99.9990) =     13.525 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.521 ± 1.333  ops/ms
ClientPb.existUser                       thrpt       3  12.865 ± 0.357  ops/ms
ClientPb.getUser                         thrpt       3  12.670 ± 1.039  ops/ms
ClientPb.listUser                        thrpt       3  10.541 ± 0.858  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.359   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.156   ms/op
ClientPb.getUser                          avgt       3   2.549 ± 0.293   ms/op
ClientPb.listUser                         avgt       3   3.056 ± 0.369   ms/op
ClientPb.createUser                     sample  376078   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.741           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.108           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.466           ms/op
ClientPb.existUser                      sample  386597   2.481 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.786           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.893           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.708           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.925           ms/op
ClientPb.getUser                        sample  378757   2.532 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.897           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.454           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.713           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.516           ms/op
ClientPb.listUser                       sample  315837   3.036 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.568           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.955           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.236           ms/op
