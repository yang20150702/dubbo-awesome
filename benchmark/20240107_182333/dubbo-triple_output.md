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
# Warmup Iteration   1: 5.073 ops/ms
# Warmup Iteration   2: 12.180 ops/ms
# Warmup Iteration   3: 12.548 ops/ms
Iteration   1: 12.544 ops/ms
Iteration   2: 12.699 ops/ms
Iteration   3: 12.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.642 ±(99.9%) 1.561 ops/ms [Average]
  (min, avg, max) = (12.544, 12.642, 12.699), stdev = 0.086
  CI (99.9%): [11.081, 14.204] (assumes normal distribution)


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
# Warmup Iteration   1: 8.641 ops/ms
# Warmup Iteration   2: 13.160 ops/ms
# Warmup Iteration   3: 13.269 ops/ms
Iteration   1: 13.195 ops/ms
Iteration   2: 13.246 ops/ms
Iteration   3: 13.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.210 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (13.188, 13.210, 13.246), stdev = 0.032
  CI (99.9%): [12.631, 13.789] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.340 ops/ms
# Warmup Iteration   2: 12.791 ops/ms
# Warmup Iteration   3: 13.030 ops/ms
Iteration   1: 13.076 ops/ms
Iteration   2: 12.969 ops/ms
Iteration   3: 13.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.020 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (12.969, 13.020, 13.076), stdev = 0.054
  CI (99.9%): [12.038, 14.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.005 ops/ms
# Warmup Iteration   2: 10.646 ops/ms
# Warmup Iteration   3: 10.789 ops/ms
Iteration   1: 10.920 ops/ms
Iteration   2: 10.930 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.862 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (10.737, 10.862, 10.930), stdev = 0.109
  CI (99.9%): [8.874, 12.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
Iteration   3: 2.434 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.461 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (2.434, 2.461, 2.479), stdev = 0.024
  CI (99.9%): [2.027, 2.895] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.036 ms/op [Average]
  (min, avg, max) = (2.420, 2.422, 2.424), stdev = 0.002
  CI (99.9%): [2.385, 2.458] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.441, 2.447, 2.451), stdev = 0.005
  CI (99.9%): [2.355, 2.538] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.005 ms/op
Iteration   1: 2.944 ±(99.9%) 0.004 ms/op
Iteration   2: 2.943 ±(99.9%) 0.005 ms/op
Iteration   3: 2.931 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.939 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.931, 2.939, 2.944), stdev = 0.007
  CI (99.9%): [2.809, 3.070] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  8.247 ms/op
                 createUser·p0.9999: 13.196 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  9.859 ms/op
                 createUser·p0.9999: 12.075 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.149 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  7.742 ms/op
                 createUser·p0.9999: 9.932 ms/op
                 createUser·p1.00:   10.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385688
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 189937 
    [ 2.500,  3.750) = 192081 
    [ 3.750,  5.000) = 2758 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     12.852 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 13.561 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.582 ms/op
                 existUser·p0.9999: 12.440 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.450 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  9.135 ms/op
                 existUser·p0.9999: 17.660 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395872
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 200794 
    [ 2.500,  3.750) = 191714 
    [ 3.750,  5.000) = 2262 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     14.097 ms/op
     p(99.9990) =     18.122 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  5.411 ms/op
                 getUser·p0.9999: 13.503 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 12.993 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  6.186 ms/op
                 getUser·p0.9999: 11.650 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386835
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 194419 
    [ 2.500,  3.750) = 188096 
    [ 3.750,  5.000) = 3411 
    [ 5.000,  6.250) = 464 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.137 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     13.800 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.468 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.009 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.420 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   2: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.600 ms/op
                 listUser·p1.00:   13.238 ms/op

Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323999
  mean =      2.960 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 102685 
    [ 2.500,  3.750) = 185278 
    [ 3.750,  5.000) = 28995 
    [ 5.000,  6.250) = 5518 
    [ 6.250,  7.500) = 694 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     13.006 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.642 ± 1.561  ops/ms
ClientPb.existUser                       thrpt       3  13.210 ± 0.579  ops/ms
ClientPb.getUser                         thrpt       3  13.020 ± 0.982  ops/ms
ClientPb.listUser                        thrpt       3  10.862 ± 1.989  ops/ms
ClientPb.createUser                       avgt       3   2.461 ± 0.434   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.036   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.092   ms/op
ClientPb.listUser                         avgt       3   2.939 ± 0.131   ms/op
ClientPb.createUser                     sample  385688   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.852           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  395872   2.422 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.729           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.864           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.481           ms/op
ClientPb.getUser                        sample  386835   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.962           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.137           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.074           ms/op
ClientPb.listUser                       sample  323999   2.960 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.238           ms/op
