# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.562 ops/ms
# Warmup Iteration   2: 3.514 ops/ms
# Warmup Iteration   3: 7.255 ops/ms
Iteration   1: 7.378 ops/ms
Iteration   2: 8.284 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.899 ±(99.9%) 8.546 ops/ms [Average]
  (min, avg, max) = (7.378, 7.899, 8.284), stdev = 0.468
  CI (99.9%): [≈ 0, 16.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 7.050 ops/ms
# Warmup Iteration   3: 8.115 ops/ms
Iteration   1: 7.938 ops/ms
Iteration   2: 8.301 ops/ms
Iteration   3: 8.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.124 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (7.938, 8.124, 8.301), stdev = 0.181
  CI (99.9%): [4.813, 11.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 5.708 ops/ms
# Warmup Iteration   3: 7.451 ops/ms
Iteration   1: 7.633 ops/ms
Iteration   2: 8.050 ops/ms
Iteration   3: 7.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.785 ±(99.9%) 4.207 ops/ms [Average]
  (min, avg, max) = (7.633, 7.785, 8.050), stdev = 0.231
  CI (99.9%): [3.578, 11.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.985 ops/ms
# Warmup Iteration   2: 5.568 ops/ms
# Warmup Iteration   3: 6.709 ops/ms
Iteration   1: 6.975 ops/ms
Iteration   2: 6.981 ops/ms
Iteration   3: 6.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.828 ±(99.9%) 4.749 ops/ms [Average]
  (min, avg, max) = (6.527, 6.828, 6.981), stdev = 0.260
  CI (99.9%): [2.079, 11.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.079 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.800 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.008 ms/op
Iteration   1: 3.950 ±(99.9%) 0.009 ms/op
Iteration   2: 3.934 ±(99.9%) 0.007 ms/op
Iteration   3: 3.997 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.960 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.934, 3.960, 3.997), stdev = 0.033
  CI (99.9%): [3.366, 4.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.041 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.270 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.004 ms/op
Iteration   1: 3.795 ±(99.9%) 0.005 ms/op
Iteration   2: 3.796 ±(99.9%) 0.007 ms/op
Iteration   3: 3.861 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.817 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.795, 3.817, 3.861), stdev = 0.038
  CI (99.9%): [3.123, 4.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 13.350 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.773 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.006 ms/op
Iteration   1: 4.021 ±(99.9%) 0.005 ms/op
Iteration   2: 3.855 ±(99.9%) 0.012 ms/op
Iteration   3: 3.856 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.911 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (3.855, 3.911, 4.021), stdev = 0.096
  CI (99.9%): [2.162, 5.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 13.600 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.133 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.006 ms/op
Iteration   1: 4.762 ±(99.9%) 0.007 ms/op
Iteration   2: 4.697 ±(99.9%) 0.012 ms/op
Iteration   3: 5.000 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.820 ±(99.9%) 2.911 ms/op [Average]
  (min, avg, max) = (4.697, 4.820, 5.000), stdev = 0.160
  CI (99.9%): [1.909, 7.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.871 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.024 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.448 ±(99.9%) 0.018 ms/op
Iteration   1: 4.060 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.810 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   7.336 ms/op
                 createUser·p0.999:  14.716 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  25.399 ms/op
                 createUser·p0.9999: 31.049 ms/op
                 createUser·p1.00:   32.080 ms/op

Iteration   3: 4.015 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  29.078 ms/op
                 createUser·p0.9999: 34.472 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240164
  mean =      3.996 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 667 
    [ 2.500,  5.000) = 227418 
    [ 5.000,  7.500) = 10336 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     24.106 ms/op
     p(99.9900) =     33.553 ms/op
     p(99.9990) =     34.747 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.579 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 5.192 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   7.071 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 25.511 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.817 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  25.435 ms/op
                 existUser·p0.9999: 28.711 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.886 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.813 ms/op
                 existUser·p0.999:  11.649 ms/op
                 existUser·p0.9999: 30.786 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253110
  mean =      3.792 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 244 
    [ 2.500,  5.000) = 244599 
    [ 5.000,  7.500) = 6386 
    [ 7.500, 10.000) = 1331 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.069 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     29.723 ms/op
     p(99.9990) =     31.473 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.057 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.713 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.014 ms/op
Iteration   1: 4.043 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.989 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   8.315 ms/op
                 getUser·p0.999:  21.707 ms/op
                 getUser·p0.9999: 31.687 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   2: 3.948 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  25.592 ms/op
                 getUser·p0.9999: 29.806 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 4.209 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  11.371 ms/op
                 getUser·p0.9999: 40.685 ms/op
                 getUser·p1.00:   41.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236042
  mean =      4.064 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221892 
    [ 5.000, 10.000) = 13294 
    [10.000, 15.000) = 589 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     39.727 ms/op
     p(99.9990) =     41.264 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.635 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.866 ±(99.9%) 0.017 ms/op
Iteration   1: 4.866 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  24.164 ms/op
                 listUser·p0.9999: 34.513 ms/op
                 listUser·p1.00:   36.176 ms/op

Iteration   2: 4.543 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.263 ms/op
                 listUser·p0.99:   8.610 ms/op
                 listUser·p0.999:  17.811 ms/op
                 listUser·p0.9999: 23.264 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.761 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.703 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 21.669 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203474
  mean =      4.719 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 167637 
    [ 5.000,  7.500) = 31050 
    [ 7.500, 10.000) = 3759 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.052 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     31.194 ms/op
     p(99.9990) =     35.191 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.899 ± 8.546  ops/ms
ClientPb.existUser                       thrpt       3   8.124 ± 3.310  ops/ms
ClientPb.getUser                         thrpt       3   7.785 ± 4.207  ops/ms
ClientPb.listUser                        thrpt       3   6.828 ± 4.749  ops/ms
ClientPb.createUser                       avgt       3   3.960 ± 0.595   ms/op
ClientPb.existUser                        avgt       3   3.817 ± 0.695   ms/op
ClientPb.getUser                          avgt       3   3.911 ± 1.749   ms/op
ClientPb.listUser                         avgt       3   4.820 ± 2.911   ms/op
ClientPb.createUser                     sample  240164   3.996 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.553           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  253110   3.792 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.645           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.069           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.723           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  236042   4.064 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.897           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.758           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.727           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.419           ms/op
ClientPb.listUser                       sample  203474   4.719 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.052           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.628           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.194           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.176           ms/op
