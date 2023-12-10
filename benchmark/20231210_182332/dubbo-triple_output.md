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
# Warmup Iteration   1: 4.694 ops/ms
# Warmup Iteration   2: 11.897 ops/ms
# Warmup Iteration   3: 12.027 ops/ms
Iteration   1: 12.466 ops/ms
Iteration   2: 12.389 ops/ms
Iteration   3: 12.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.470 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (12.389, 12.470, 12.556), stdev = 0.083
  CI (99.9%): [10.947, 13.994] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.737 ops/ms
# Warmup Iteration   3: 12.810 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 12.804 ops/ms
Iteration   3: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.745 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (12.706, 12.745, 12.804), stdev = 0.052
  CI (99.9%): [11.796, 13.693] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ops/ms
# Warmup Iteration   2: 12.469 ops/ms
# Warmup Iteration   3: 12.687 ops/ms
Iteration   1: 12.619 ops/ms
Iteration   2: 12.715 ops/ms
Iteration   3: 12.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.681 ±(99.9%) 0.983 ops/ms [Average]
  (min, avg, max) = (12.619, 12.681, 12.715), stdev = 0.054
  CI (99.9%): [11.697, 13.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.867 ops/ms
# Warmup Iteration   2: 10.533 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.805 ops/ms
Iteration   2: 10.821 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.778 ±(99.9%) 1.110 ops/ms [Average]
  (min, avg, max) = (10.709, 10.778, 10.821), stdev = 0.061
  CI (99.9%): [9.668, 11.888] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.004 ms/op
Iteration   1: 2.574 ±(99.9%) 0.004 ms/op
Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
Iteration   3: 2.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.561, 2.569, 2.574), stdev = 0.007
  CI (99.9%): [2.445, 2.692] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.469, 2.483, 2.497), stdev = 0.014
  CI (99.9%): [2.226, 2.740] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.553 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (2.546, 2.553, 2.558), stdev = 0.006
  CI (99.9%): [2.437, 2.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.005 ms/op
Iteration   1: 3.054 ±(99.9%) 0.005 ms/op
Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
Iteration   3: 3.051 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.050 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (3.045, 3.050, 3.054), stdev = 0.005
  CI (99.9%): [2.966, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.766 ms/op
                 createUser·p0.9999: 14.107 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.812 ms/op
                 createUser·p0.9999: 12.151 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.701 ms/op
                 createUser·p0.9999: 11.731 ms/op
                 createUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377982
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 182169 
    [ 2.500,  3.750) = 192268 
    [ 3.750,  5.000) = 2801 
    [ 5.000,  6.250) = 269 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.290 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 13.110 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  5.699 ms/op
                 existUser·p0.9999: 12.778 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.897 ms/op
                 existUser·p0.999:  9.400 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387389
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 192952 
    [ 2.500,  3.750) = 190827 
    [ 3.750,  5.000) = 2826 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      7.157 ms/op
     p(99.9900) =     12.817 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  9.775 ms/op
                 getUser·p0.9999: 14.623 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  5.628 ms/op
                 getUser·p0.9999: 11.908 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 11.960 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380666
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 186455 
    [ 2.500,  3.750) = 189777 
    [ 3.750,  5.000) = 3595 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      6.616 ms/op
     p(99.9900) =     13.188 ms/op
     p(99.9990) =     14.814 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.781 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
Iteration   1: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.608 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 10.790 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  10.401 ms/op
                 listUser·p0.9999: 11.787 ms/op
                 listUser·p1.00:   12.927 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.827 ms/op
                 listUser·p0.9999: 12.796 ms/op
                 listUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315722
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 85738 
    [ 2.500,  3.750) = 190184 
    [ 3.750,  5.000) = 32419 
    [ 5.000,  6.250) = 5998 
    [ 6.250,  7.500) = 587 
    [ 7.500,  8.750) = 155 
    [ 8.750, 10.000) = 278 
    [10.000, 11.250) = 197 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     12.335 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.470 ± 1.523  ops/ms
ClientPb.existUser                       thrpt       3  12.745 ± 0.949  ops/ms
ClientPb.getUser                         thrpt       3  12.681 ± 0.983  ops/ms
ClientPb.listUser                        thrpt       3  10.778 ± 1.110  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.124   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.257   ms/op
ClientPb.getUser                          avgt       3   2.553 ± 0.116   ms/op
ClientPb.listUser                         avgt       3   3.050 ± 0.084   ms/op
ClientPb.createUser                     sample  377982   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  387389   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.886           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.157           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.817           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.566           ms/op
ClientPb.getUser                        sample  380666   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.672           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.616           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.188           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  315722   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.880           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.927           ms/op
