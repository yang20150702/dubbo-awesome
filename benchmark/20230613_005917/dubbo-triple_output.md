# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.137 ops/ms
# Warmup Iteration   2: 5.389 ops/ms
# Warmup Iteration   3: 8.264 ops/ms
Iteration   1: 9.307 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.375 ±(99.9%) 1.061 ops/ms [Average]
  (min, avg, max) = (9.307, 9.375, 9.410), stdev = 0.058
  CI (99.9%): [8.314, 10.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.839 ops/ms
# Warmup Iteration   2: 8.235 ops/ms
# Warmup Iteration   3: 9.696 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.634 ±(99.9%) 5.817 ops/ms [Average]
  (min, avg, max) = (9.268, 9.634, 9.852), stdev = 0.319
  CI (99.9%): [3.818, 15.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.781 ops/ms
# Warmup Iteration   2: 8.450 ops/ms
# Warmup Iteration   3: 9.168 ops/ms
Iteration   1: 9.402 ops/ms
Iteration   2: 9.680 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.527 ±(99.9%) 2.566 ops/ms [Average]
  (min, avg, max) = (9.402, 9.527, 9.680), stdev = 0.141
  CI (99.9%): [6.961, 12.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.993 ops/ms
# Warmup Iteration   2: 7.334 ops/ms
# Warmup Iteration   3: 7.748 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 7.839 ops/ms
Iteration   3: 8.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.978 ±(99.9%) 2.676 ops/ms [Average]
  (min, avg, max) = (7.839, 7.978, 8.132), stdev = 0.147
  CI (99.9%): [5.301, 10.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.456 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.007 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
Iteration   2: 3.328 ±(99.9%) 0.006 ms/op
Iteration   3: 3.412 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.370 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.328, 3.370, 3.412), stdev = 0.042
  CI (99.9%): [2.600, 4.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.946 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.005 ms/op
Iteration   1: 3.301 ±(99.9%) 0.005 ms/op
Iteration   2: 3.196 ±(99.9%) 0.009 ms/op
Iteration   3: 3.207 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.235 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.196, 3.235, 3.301), stdev = 0.058
  CI (99.9%): [2.182, 4.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.008 ms/op
Iteration   1: 3.421 ±(99.9%) 0.006 ms/op
Iteration   2: 3.575 ±(99.9%) 0.006 ms/op
Iteration   3: 3.401 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 1.737 ms/op [Average]
  (min, avg, max) = (3.401, 3.465, 3.575), stdev = 0.095
  CI (99.9%): [1.728, 5.203] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.077 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.013 ms/op
Iteration   1: 3.978 ±(99.9%) 0.013 ms/op
Iteration   2: 3.986 ±(99.9%) 0.010 ms/op
Iteration   3: 3.906 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.956 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (3.906, 3.956, 3.986), stdev = 0.044
  CI (99.9%): [3.153, 4.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.011 ms/op
Iteration   1: 3.502 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  20.506 ms/op
                 createUser·p0.9999: 35.652 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   2: 3.365 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  21.918 ms/op
                 createUser·p0.9999: 24.871 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  19.360 ms/op
                 createUser·p0.9999: 32.375 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277463
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10674 
    [ 2.500,  5.000) = 258769 
    [ 5.000,  7.500) = 7002 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     19.713 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.419 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
Iteration   1: 3.349 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  12.116 ms/op
                 existUser·p0.9999: 22.330 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.311 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  15.898 ms/op
                 existUser·p0.9999: 33.107 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.150 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  20.019 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285123
  mean =      3.365 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18205 
    [ 2.500,  5.000) = 262720 
    [ 5.000,  7.500) = 3513 
    [ 7.500, 10.000) = 240 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     14.088 ms/op
     p(99.9900) =     31.522 ms/op
     p(99.9990) =     33.630 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.156 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.013 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.821 ms/op
                 getUser·p0.999:  19.810 ms/op
                 getUser·p0.9999: 23.061 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.111 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  22.057 ms/op
                 getUser·p0.9999: 25.972 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  18.679 ms/op
                 getUser·p0.9999: 28.401 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277426
  mean =      3.460 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6185 
    [ 2.500,  5.000) = 264635 
    [ 5.000,  7.500) = 5608 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     19.090 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     28.516 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.369 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  20.141 ms/op
                 listUser·p0.9999: 24.230 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   2: 4.060 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.634 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.880 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.119 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 18.735 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240332
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 232262 
    [ 5.000,  7.500) = 6161 
    [ 7.500, 10.000) = 1117 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.375 ± 1.061  ops/ms
ClientPb.existUser                       thrpt       3   9.634 ± 5.817  ops/ms
ClientPb.getUser                         thrpt       3   9.527 ± 2.566  ops/ms
ClientPb.listUser                        thrpt       3   7.978 ± 2.676  ops/ms
ClientPb.createUser                       avgt       3   3.370 ± 0.771   ms/op
ClientPb.existUser                        avgt       3   3.235 ± 1.053   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 1.737   ms/op
ClientPb.listUser                         avgt       3   3.956 ± 0.804   ms/op
ClientPb.createUser                     sample  277463   3.458 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.910           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  285123   3.365 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.323           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.088           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.522           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  277426   3.460 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.571           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.090           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.608           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  240332   3.995 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.298           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.199           ms/op
