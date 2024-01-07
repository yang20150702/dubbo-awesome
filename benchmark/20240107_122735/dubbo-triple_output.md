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
# Warmup Iteration   1: 4.954 ops/ms
# Warmup Iteration   2: 12.169 ops/ms
# Warmup Iteration   3: 12.298 ops/ms
Iteration   1: 12.682 ops/ms
Iteration   2: 12.673 ops/ms
Iteration   3: 12.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.726 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (12.673, 12.726, 12.823), stdev = 0.084
  CI (99.9%): [11.190, 14.262] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.997 ops/ms
# Warmup Iteration   2: 13.226 ops/ms
# Warmup Iteration   3: 13.184 ops/ms
Iteration   1: 13.114 ops/ms
Iteration   2: 13.202 ops/ms
Iteration   3: 13.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.163 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (13.114, 13.163, 13.202), stdev = 0.045
  CI (99.9%): [12.344, 13.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.926 ops/ms
# Warmup Iteration   2: 12.689 ops/ms
# Warmup Iteration   3: 12.943 ops/ms
Iteration   1: 13.094 ops/ms
Iteration   2: 13.033 ops/ms
Iteration   3: 13.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.061 ±(99.9%) 0.559 ops/ms [Average]
  (min, avg, max) = (13.033, 13.061, 13.094), stdev = 0.031
  CI (99.9%): [12.502, 13.620] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.824 ops/ms
# Warmup Iteration   2: 10.482 ops/ms
# Warmup Iteration   3: 10.580 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.621 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (10.580, 10.621, 10.648), stdev = 0.036
  CI (99.9%): [9.966, 11.277] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.003 ms/op
Iteration   3: 2.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.526, 2.534, 2.540), stdev = 0.007
  CI (99.9%): [2.408, 2.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.420 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (2.420, 2.458, 2.500), stdev = 0.040
  CI (99.9%): [1.725, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.526 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (2.502, 2.526, 2.544), stdev = 0.022
  CI (99.9%): [2.132, 2.919] (assumes normal distribution)


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
# Warmup Iteration   1: 5.068 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.005 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.051 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.043, 3.051, 3.063), stdev = 0.011
  CI (99.9%): [2.854, 3.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.744 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.585 ±(99.9%) 0.006 ms/op
Iteration   1: 2.585 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  12.180 ms/op
                 createUser·p0.9999: 14.139 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  10.691 ms/op
                 createUser·p0.9999: 14.348 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.066 ms/op
                 createUser·p0.999:  8.755 ms/op
                 createUser·p0.9999: 11.562 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375097
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 177643 
    [ 2.500,  3.750) = 192217 
    [ 3.750,  5.000) = 4148 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.813 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     14.901 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  11.922 ms/op
                 existUser·p0.9999: 14.086 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  5.799 ms/op
                 existUser·p0.9999: 14.158 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  7.969 ms/op
                 existUser·p0.9999: 13.060 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383571
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 187318 
    [ 2.500,  3.750) = 191886 
    [ 3.750,  5.000) = 3510 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.225 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     14.571 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.590 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  12.300 ms/op
                 getUser·p0.9999: 14.598 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  10.837 ms/op
                 getUser·p0.9999: 15.201 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  5.513 ms/op
                 getUser·p0.9999: 11.579 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375654
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 181798 
    [ 2.500,  3.750) = 188936 
    [ 3.750,  5.000) = 3944 
    [ 5.000,  6.250) = 553 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      5.970 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.009 ms/op
Iteration   1: 3.108 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.860 ms/op
                 listUser·p1.00:   13.664 ms/op

Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.597 ms/op
                 listUser·p0.9999: 13.707 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   3: 3.069 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.158 ms/op
                 listUser·p0.9999: 15.270 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311212
  mean =      3.082 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 80115 
    [ 2.500,  3.750) = 186987 
    [ 3.750,  5.000) = 35275 
    [ 5.000,  6.250) = 7039 
    [ 6.250,  7.500) = 967 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 169 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     14.099 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.726 ± 1.536  ops/ms
ClientPb.existUser                       thrpt       3  13.163 ± 0.818  ops/ms
ClientPb.getUser                         thrpt       3  13.061 ± 0.559  ops/ms
ClientPb.listUser                        thrpt       3  10.621 ± 0.656  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.126   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.733   ms/op
ClientPb.getUser                          avgt       3   2.526 ± 0.393   ms/op
ClientPb.listUser                         avgt       3   3.051 ± 0.197   ms/op
ClientPb.createUser                     sample  375097   2.556 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.647           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.813           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.104           ms/op
ClientPb.existUser                      sample  383571   2.500 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.730           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.225           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  375654   2.553 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.909           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.970           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.647           ms/op
ClientPb.listUser                       sample  311212   3.082 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.099           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.466           ms/op
