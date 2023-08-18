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
# Warmup Iteration   1: 1.670 ops/ms
# Warmup Iteration   2: 3.626 ops/ms
# Warmup Iteration   3: 7.374 ops/ms
Iteration   1: 7.637 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.110 ±(99.9%) 8.106 ops/ms [Average]
  (min, avg, max) = (7.637, 8.110, 8.518), stdev = 0.444
  CI (99.9%): [0.004, 16.217] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 7.421 ops/ms
# Warmup Iteration   3: 8.496 ops/ms
Iteration   1: 8.419 ops/ms
Iteration   2: 9.091 ops/ms
Iteration   3: 8.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.780 ±(99.9%) 6.184 ops/ms [Average]
  (min, avg, max) = (8.419, 8.780, 9.091), stdev = 0.339
  CI (99.9%): [2.596, 14.964] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 7.967 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 8.642 ops/ms
Iteration   2: 8.348 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.455 ±(99.9%) 2.970 ops/ms [Average]
  (min, avg, max) = (8.348, 8.455, 8.642), stdev = 0.163
  CI (99.9%): [5.484, 11.425] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.252 ops/ms
# Warmup Iteration   2: 6.060 ops/ms
# Warmup Iteration   3: 6.946 ops/ms
Iteration   1: 7.143 ops/ms
Iteration   2: 6.920 ops/ms
Iteration   3: 6.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.016 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (6.920, 7.016, 7.143), stdev = 0.114
  CI (99.9%): [4.930, 9.102] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.841 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.982 ±(99.9%) 0.008 ms/op
Iteration   2: 3.962 ±(99.9%) 0.014 ms/op
Iteration   3: 3.926 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.957 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.926, 3.957, 3.982), stdev = 0.028
  CI (99.9%): [3.440, 4.473] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.029 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.009 ms/op
Iteration   1: 3.692 ±(99.9%) 0.004 ms/op
Iteration   2: 3.625 ±(99.9%) 0.005 ms/op
Iteration   3: 3.677 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.665 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.625, 3.665, 3.692), stdev = 0.035
  CI (99.9%): [3.022, 4.307] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.774 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.005 ms/op
Iteration   1: 3.748 ±(99.9%) 0.005 ms/op
Iteration   2: 3.634 ±(99.9%) 0.007 ms/op
Iteration   3: 3.798 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.727 ±(99.9%) 1.537 ms/op [Average]
  (min, avg, max) = (3.634, 3.727, 3.798), stdev = 0.084
  CI (99.9%): [2.189, 5.264] (assumes normal distribution)


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
# Warmup Iteration   1: 12.234 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.005 ms/op
Iteration   1: 4.672 ±(99.9%) 0.008 ms/op
Iteration   2: 4.504 ±(99.9%) 0.015 ms/op
Iteration   3: 4.490 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.555 ±(99.9%) 1.840 ms/op [Average]
  (min, avg, max) = (4.490, 4.555, 4.672), stdev = 0.101
  CI (99.9%): [2.715, 6.396] (assumes normal distribution)


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
# Warmup Iteration   1: 10.376 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.016 ms/op
Iteration   1: 3.950 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  14.634 ms/op
                 createUser·p0.9999: 26.965 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 26.343 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 4.003 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  25.395 ms/op
                 createUser·p0.9999: 32.251 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241427
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 507 
    [ 2.500,  5.000) = 225349 
    [ 5.000,  7.500) = 13109 
    [ 7.500, 10.000) = 1707 
    [10.000, 12.500) = 445 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     22.910 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 10.267 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.013 ms/op
Iteration   1: 3.690 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   7.114 ms/op
                 existUser·p0.999:  12.194 ms/op
                 existUser·p0.9999: 28.638 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  12.850 ms/op
                 existUser·p0.9999: 26.335 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.733 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  27.444 ms/op
                 existUser·p0.9999: 30.488 ms/op
                 existUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255695
  mean =      3.756 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1592 
    [ 2.500,  5.000) = 244043 
    [ 5.000,  7.500) = 7938 
    [ 7.500, 10.000) = 1376 
    [10.000, 12.500) = 461 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     16.830 ms/op
     p(99.9900) =     30.062 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.005 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.343 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.015 ms/op
Iteration   1: 3.974 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  14.065 ms/op
                 getUser·p0.9999: 23.360 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   2: 3.859 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  23.298 ms/op
                 getUser·p0.9999: 42.533 ms/op
                 getUser·p1.00:   43.778 ms/op

Iteration   3: 3.830 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  11.314 ms/op
                 getUser·p0.9999: 29.969 ms/op
                 getUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246943
  mean =      3.887 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 232382 
    [ 5.000, 10.000) = 13870 
    [10.000, 15.000) = 466 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 124 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     41.963 ms/op
     p(99.9990) =     42.861 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


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
# Warmup Iteration   1: 13.399 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.306 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.646 ±(99.9%) 0.018 ms/op
Iteration   1: 4.573 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  22.874 ms/op
                 listUser·p0.9999: 28.869 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 4.541 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.780 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  17.848 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.463 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  15.894 ms/op
                 listUser·p0.9999: 18.469 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212032
  mean =      4.525 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 187808 
    [ 5.000,  7.500) = 18841 
    [ 7.500, 10.000) = 3950 
    [10.000, 12.500) = 919 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     27.309 ms/op
     p(99.9990) =     29.992 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.110 ± 8.106  ops/ms
ClientPb.existUser                       thrpt       3   8.780 ± 6.184  ops/ms
ClientPb.getUser                         thrpt       3   8.455 ± 2.970  ops/ms
ClientPb.listUser                        thrpt       3   7.016 ± 2.086  ops/ms
ClientPb.createUser                       avgt       3   3.957 ± 0.516   ms/op
ClientPb.existUser                        avgt       3   3.665 ± 0.643   ms/op
ClientPb.getUser                          avgt       3   3.727 ± 1.537   ms/op
ClientPb.listUser                         avgt       3   4.555 ± 1.840   ms/op
ClientPb.createUser                     sample  241427   3.973 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.313           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.528           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.910           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.802           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  255695   3.756 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.053           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.830           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.062           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.047           ms/op
ClientPb.getUser                        sample  246943   3.887 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.963           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.778           ms/op
ClientPb.listUser                       sample  212032   4.525 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.142           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.990           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.309           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
