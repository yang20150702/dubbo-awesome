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
# Warmup Iteration   1: 2.613 ops/ms
# Warmup Iteration   2: 5.758 ops/ms
# Warmup Iteration   3: 8.981 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 10.212 ops/ms
Iteration   3: 9.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.941 ±(99.9%) 5.307 ops/ms [Average]
  (min, avg, max) = (9.634, 9.941, 10.212), stdev = 0.291
  CI (99.9%): [4.634, 15.248] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 10.390 ops/ms
Iteration   1: 10.761 ops/ms
Iteration   2: 10.152 ops/ms
Iteration   3: 10.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.319 ±(99.9%) 7.050 ops/ms [Average]
  (min, avg, max) = (10.044, 10.319, 10.761), stdev = 0.386
  CI (99.9%): [3.269, 17.369] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.279 ops/ms
# Warmup Iteration   2: 8.542 ops/ms
# Warmup Iteration   3: 9.915 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 10.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.979 ±(99.9%) 2.585 ops/ms [Average]
  (min, avg, max) = (9.819, 9.979, 10.090), stdev = 0.142
  CI (99.9%): [7.394, 12.563] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.219 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.494 ops/ms
Iteration   3: 8.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.468 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (8.422, 8.468, 8.494), stdev = 0.040
  CI (99.9%): [7.735, 9.201] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.820 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.004 ms/op
Iteration   1: 3.287 ±(99.9%) 0.008 ms/op
Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
Iteration   3: 3.101 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.151 ±(99.9%) 2.167 ms/op [Average]
  (min, avg, max) = (3.065, 3.151, 3.287), stdev = 0.119
  CI (99.9%): [0.983, 5.318] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.203 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.110 ±(99.9%) 2.261 ms/op [Average]
  (min, avg, max) = (3.027, 3.110, 3.252), stdev = 0.124
  CI (99.9%): [0.849, 5.370] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.022 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.002 ms/op
Iteration   1: 3.251 ±(99.9%) 0.004 ms/op
Iteration   2: 3.179 ±(99.9%) 0.005 ms/op
Iteration   3: 3.173 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.201 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.173, 3.201, 3.251), stdev = 0.043
  CI (99.9%): [2.412, 3.990] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.967 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.005 ms/op
Iteration   1: 3.827 ±(99.9%) 0.007 ms/op
Iteration   2: 3.718 ±(99.9%) 0.008 ms/op
Iteration   3: 3.779 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.774 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.718, 3.774, 3.827), stdev = 0.055
  CI (99.9%): [2.773, 4.776] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.092 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 20.078 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.304 ms/op
                 createUser·p0.999:  15.335 ms/op
                 createUser·p0.9999: 25.328 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  17.136 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300140
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7115 
    [ 2.500,  5.000) = 288484 
    [ 5.000,  7.500) = 3824 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.379 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     23.756 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 7.724 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.099 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  7.937 ms/op
                 existUser·p0.9999: 19.847 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.444 ms/op
                 existUser·p0.999:  12.022 ms/op
                 existUser·p0.9999: 27.347 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  14.362 ms/op
                 existUser·p0.9999: 23.127 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306967
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12167 
    [ 2.500,  5.000) = 289361 
    [ 5.000,  7.500) = 4670 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     13.944 ms/op
     p(99.9900) =     25.513 ms/op
     p(99.9990) =     27.748 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 7.975 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.010 ms/op
Iteration   1: 3.251 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  14.134 ms/op
                 getUser·p0.9999: 20.682 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 23.525 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   3: 3.324 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.287 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  17.415 ms/op
                 getUser·p0.9999: 28.070 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295343
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24710 
    [ 2.500,  5.000) = 263455 
    [ 5.000,  7.500) = 6300 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     26.000 ms/op
     p(99.9990) =     28.492 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 8.997 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.012 ms/op
Iteration   1: 3.697 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.536 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  19.052 ms/op
                 listUser·p0.9999: 28.137 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 3.699 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.370 ms/op
                 listUser·p0.9999: 13.589 ms/op
                 listUser·p1.00:   14.074 ms/op

Iteration   3: 3.776 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.316 ms/op
                 listUser·p0.999:  15.453 ms/op
                 listUser·p0.9999: 16.458 ms/op
                 listUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257861
  mean =      3.724 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 250936 
    [ 5.000,  7.500) = 5123 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.060 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     30.916 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.941 ± 5.307  ops/ms
ClientPb.existUser                       thrpt       3  10.319 ± 7.050  ops/ms
ClientPb.getUser                         thrpt       3   9.979 ± 2.585  ops/ms
ClientPb.listUser                        thrpt       3   8.468 ± 0.733  ops/ms
ClientPb.createUser                       avgt       3   3.151 ± 2.167   ms/op
ClientPb.existUser                        avgt       3   3.110 ± 2.261   ms/op
ClientPb.getUser                          avgt       3   3.201 ± 0.789   ms/op
ClientPb.listUser                         avgt       3   3.774 ± 1.001   ms/op
ClientPb.createUser                     sample  300140   3.194 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.379           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.712           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.756           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  306967   3.126 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.513           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.886           ms/op
ClientPb.getUser                        sample  295343   3.247 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.287           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.959           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.000           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.869           ms/op
ClientPb.listUser                       sample  257861   3.724 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.870           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
