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
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 3.423 ops/ms
# Warmup Iteration   3: 7.072 ops/ms
Iteration   1: 7.495 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 7.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.720 ±(99.9%) 5.122 ops/ms [Average]
  (min, avg, max) = (7.495, 7.720, 8.035), stdev = 0.281
  CI (99.9%): [2.598, 12.842] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 6.909 ops/ms
# Warmup Iteration   3: 8.075 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.607 ops/ms
Iteration   3: 8.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.509 ±(99.9%) 5.389 ops/ms [Average]
  (min, avg, max) = (8.177, 8.509, 8.743), stdev = 0.295
  CI (99.9%): [3.120, 13.898] (assumes normal distribution)


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
# Warmup Iteration   1: 2.078 ops/ms
# Warmup Iteration   2: 6.556 ops/ms
# Warmup Iteration   3: 8.129 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 8.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.983 ±(99.9%) 2.766 ops/ms [Average]
  (min, avg, max) = (7.854, 7.983, 8.150), stdev = 0.152
  CI (99.9%): [5.217, 10.750] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.956 ops/ms
# Warmup Iteration   2: 5.113 ops/ms
# Warmup Iteration   3: 6.597 ops/ms
Iteration   1: 6.803 ops/ms
Iteration   2: 6.830 ops/ms
Iteration   3: 6.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.864 ±(99.9%) 1.535 ops/ms [Average]
  (min, avg, max) = (6.803, 6.864, 6.960), stdev = 0.084
  CI (99.9%): [5.329, 8.399] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.826 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.112 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.006 ms/op
Iteration   1: 3.907 ±(99.9%) 0.013 ms/op
Iteration   2: 3.991 ±(99.9%) 0.006 ms/op
Iteration   3: 4.093 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.997 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (3.907, 3.997, 4.093), stdev = 0.093
  CI (99.9%): [2.297, 5.697] (assumes normal distribution)


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
# Warmup Iteration   1: 13.262 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.007 ms/op
Iteration   1: 4.059 ±(99.9%) 0.011 ms/op
Iteration   2: 3.799 ±(99.9%) 0.007 ms/op
Iteration   3: 3.808 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.888 ±(99.9%) 2.690 ms/op [Average]
  (min, avg, max) = (3.799, 3.888, 4.059), stdev = 0.147
  CI (99.9%): [1.198, 6.579] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.336 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.895 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.006 ms/op
Iteration   1: 4.060 ±(99.9%) 0.007 ms/op
Iteration   2: 3.951 ±(99.9%) 0.012 ms/op
Iteration   3: 4.108 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.040 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.951, 4.040, 4.108), stdev = 0.080
  CI (99.9%): [2.573, 5.507] (assumes normal distribution)


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
# Warmup Iteration   1: 15.599 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.410 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.748 ±(99.9%) 0.008 ms/op
Iteration   1: 4.667 ±(99.9%) 0.008 ms/op
Iteration   2: 4.546 ±(99.9%) 0.013 ms/op
Iteration   3: 4.635 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.616 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (4.546, 4.616, 4.667), stdev = 0.063
  CI (99.9%): [3.475, 5.757] (assumes normal distribution)


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
# Warmup Iteration   1: 14.156 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.480 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.583 ±(99.9%) 0.020 ms/op
Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.909 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.017 ms/op
                 createUser·p0.999:  24.702 ms/op
                 createUser·p0.9999: 28.380 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  14.668 ms/op
                 createUser·p0.9999: 27.920 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 3.889 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  28.019 ms/op
                 createUser·p0.9999: 32.437 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241310
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 310 
    [ 2.500,  5.000) = 228000 
    [ 5.000,  7.500) = 11039 
    [ 7.500, 10.000) = 1169 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     24.664 ms/op
     p(99.9900) =     32.043 ms/op
     p(99.9990) =     33.132 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.178 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.015 ms/op
Iteration   1: 3.880 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  22.806 ms/op
                 existUser·p0.9999: 38.207 ms/op
                 existUser·p1.00:   38.863 ms/op

Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  16.941 ms/op
                 existUser·p0.9999: 33.767 ms/op
                 existUser·p1.00:   34.603 ms/op

Iteration   3: 3.818 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.896 ms/op
                 existUser·p0.999:  27.144 ms/op
                 existUser·p0.9999: 31.342 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250142
  mean =      3.837 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 366 
    [ 2.500,  5.000) = 239690 
    [ 5.000,  7.500) = 8248 
    [ 7.500, 10.000) = 1143 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     20.929 ms/op
     p(99.9900) =     37.026 ms/op
     p(99.9990) =     38.797 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.859 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.015 ms/op
Iteration   1: 3.957 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  23.404 ms/op
                 getUser·p0.9999: 26.635 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.784 ms/op
                 getUser·p0.999:  10.875 ms/op
                 getUser·p0.9999: 27.765 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 4.091 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 34.079 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240765
  mean =      3.986 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 227447 
    [ 5.000,  7.500) = 11340 
    [ 7.500, 10.000) = 1391 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.068 ms/op
     p(99.9900) =     33.242 ms/op
     p(99.9990) =     34.183 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.972 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.015 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.019 ms/op
Iteration   1: 4.726 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  25.150 ms/op
                 listUser·p0.9999: 28.490 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.604 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  20.268 ms/op
                 listUser·p0.9999: 23.759 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 4.580 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207059
  mean =      4.636 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 181245 
    [ 5.000,  7.500) = 21352 
    [ 7.500, 10.000) = 3491 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     20.773 ms/op
     p(99.9900) =     27.174 ms/op
     p(99.9990) =     29.384 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.720 ± 5.122  ops/ms
ClientPb.existUser                       thrpt       3   8.509 ± 5.389  ops/ms
ClientPb.getUser                         thrpt       3   7.983 ± 2.766  ops/ms
ClientPb.listUser                        thrpt       3   6.864 ± 1.535  ops/ms
ClientPb.createUser                       avgt       3   3.997 ± 1.700   ms/op
ClientPb.existUser                        avgt       3   3.888 ± 2.690   ms/op
ClientPb.getUser                          avgt       3   4.040 ± 1.467   ms/op
ClientPb.listUser                         avgt       3   4.616 ± 1.141   ms/op
ClientPb.createUser                     sample  241310   3.976 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.135           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.664           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.043           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.260           ms/op
ClientPb.existUser                      sample  250142   3.837 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.012           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.929           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.026           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.863           ms/op
ClientPb.getUser                        sample  240765   3.986 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.538           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.068           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.242           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  207059   4.636 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.773           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
