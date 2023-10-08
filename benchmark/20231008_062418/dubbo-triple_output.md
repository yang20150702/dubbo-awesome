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
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 3.862 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 7.848 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.152 ±(99.9%) 5.195 ops/ms [Average]
  (min, avg, max) = (7.848, 8.152, 8.413), stdev = 0.285
  CI (99.9%): [2.958, 13.347] (assumes normal distribution)


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
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 7.060 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 8.650 ops/ms
Iteration   2: 8.563 ops/ms
Iteration   3: 8.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.638 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (8.563, 8.638, 8.701), stdev = 0.070
  CI (99.9%): [7.360, 9.917] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.343 ops/ms
# Warmup Iteration   2: 6.774 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 7.679 ops/ms
Iteration   2: 7.853 ops/ms
Iteration   3: 7.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.779 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (7.679, 7.779, 7.853), stdev = 0.090
  CI (99.9%): [6.143, 9.415] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.987 ops/ms
# Warmup Iteration   3: 6.787 ops/ms
Iteration   1: 6.663 ops/ms
Iteration   2: 6.807 ops/ms
Iteration   3: 6.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.780 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (6.663, 6.780, 6.871), stdev = 0.107
  CI (99.9%): [4.832, 8.728] (assumes normal distribution)


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
# Warmup Iteration   1: 13.314 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.005 ms/op
Iteration   1: 3.874 ±(99.9%) 0.007 ms/op
Iteration   2: 3.836 ±(99.9%) 0.008 ms/op
Iteration   3: 4.040 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.917 ±(99.9%) 1.980 ms/op [Average]
  (min, avg, max) = (3.836, 3.917, 4.040), stdev = 0.109
  CI (99.9%): [1.936, 5.897] (assumes normal distribution)


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
# Warmup Iteration   1: 10.034 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.005 ms/op
Iteration   1: 3.841 ±(99.9%) 0.005 ms/op
Iteration   2: 3.819 ±(99.9%) 0.003 ms/op
Iteration   3: 3.861 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.840 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.819, 3.840, 3.861), stdev = 0.021
  CI (99.9%): [3.455, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 12.388 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.005 ms/op
Iteration   1: 3.985 ±(99.9%) 0.006 ms/op
Iteration   2: 3.950 ±(99.9%) 0.004 ms/op
Iteration   3: 3.917 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.951 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.917, 3.951, 3.985), stdev = 0.034
  CI (99.9%): [3.334, 4.568] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.320 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.688 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.633 ±(99.9%) 0.007 ms/op
Iteration   1: 4.812 ±(99.9%) 0.006 ms/op
Iteration   2: 4.664 ±(99.9%) 0.009 ms/op
Iteration   3: 4.479 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.651 ±(99.9%) 3.043 ms/op [Average]
  (min, avg, max) = (4.479, 4.651, 4.812), stdev = 0.167
  CI (99.9%): [1.608, 7.694] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.296 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.018 ms/op
Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  15.476 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   2: 3.937 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  24.927 ms/op
                 createUser·p0.9999: 27.618 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   3: 3.977 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  26.120 ms/op
                 createUser·p0.9999: 31.515 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245870
  mean =      3.904 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 893 
    [ 2.500,  5.000) = 231764 
    [ 5.000,  7.500) = 10155 
    [ 7.500, 10.000) = 2322 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     30.684 ms/op
     p(99.9990) =     32.625 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.167 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.016 ms/op
Iteration   1: 3.926 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.873 ms/op
                 existUser·p0.999:  23.333 ms/op
                 existUser·p0.9999: 39.312 ms/op
                 existUser·p1.00:   39.846 ms/op

Iteration   2: 3.886 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  15.476 ms/op
                 existUser·p0.9999: 27.837 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 4.021 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  27.926 ms/op
                 existUser·p0.9999: 30.282 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243558
  mean =      3.944 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 713 
    [ 2.500,  5.000) = 225767 
    [ 5.000,  7.500) = 13694 
    [ 7.500, 10.000) = 2361 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     23.411 ms/op
     p(99.9900) =     37.136 ms/op
     p(99.9990) =     39.723 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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
# Warmup Iteration   1: 10.198 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.018 ms/op
Iteration   1: 4.055 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   9.182 ms/op
                 getUser·p0.999:  20.138 ms/op
                 getUser·p0.9999: 23.597 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  24.193 ms/op
                 getUser·p0.9999: 26.778 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 3.962 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  18.393 ms/op
                 getUser·p0.9999: 27.654 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242219
  mean =      3.961 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 469 
    [ 2.500,  5.000) = 228170 
    [ 5.000,  7.500) = 9963 
    [ 7.500, 10.000) = 2370 
    [10.000, 12.500) = 621 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 116 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      8.158 ms/op
     p(99.9000) =     20.637 ms/op
     p(99.9900) =     27.190 ms/op
     p(99.9990) =     28.680 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 14.336 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.289 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.805 ±(99.9%) 0.018 ms/op
Iteration   1: 4.634 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  22.381 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 4.762 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.717 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  20.000 ms/op
                 listUser·p0.9999: 28.115 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204188
  mean =      4.704 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 168863 
    [ 5.000,  7.500) = 29433 
    [ 7.500, 10.000) = 4564 
    [10.000, 12.500) = 513 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     29.490 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.152 ± 5.195  ops/ms
ClientPb.existUser                       thrpt       3   8.638 ± 1.279  ops/ms
ClientPb.getUser                         thrpt       3   7.779 ± 1.636  ops/ms
ClientPb.listUser                        thrpt       3   6.780 ± 1.948  ops/ms
ClientPb.createUser                       avgt       3   3.917 ± 1.980   ms/op
ClientPb.existUser                        avgt       3   3.840 ± 0.385   ms/op
ClientPb.getUser                          avgt       3   3.951 ± 0.617   ms/op
ClientPb.listUser                         avgt       3   4.651 ± 3.043   ms/op
ClientPb.createUser                     sample  245870   3.904 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.953           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.684           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.932           ms/op
ClientPb.existUser                      sample  243558   3.944 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.694           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.897           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.411           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.136           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.846           ms/op
ClientPb.getUser                        sample  242219   3.961 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.158           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.637           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.190           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  204188   4.704 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.389           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.923           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.165           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
