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
# Warmup Iteration   1: 1.215 ops/ms
# Warmup Iteration   2: 3.286 ops/ms
# Warmup Iteration   3: 6.224 ops/ms
Iteration   1: 5.902 ops/ms
Iteration   2: 6.500 ops/ms
Iteration   3: 6.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.284 ±(99.9%) 6.051 ops/ms [Average]
  (min, avg, max) = (5.902, 6.284, 6.500), stdev = 0.332
  CI (99.9%): [0.233, 12.335] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.866 ops/ms
# Warmup Iteration   2: 5.920 ops/ms
# Warmup Iteration   3: 6.345 ops/ms
Iteration   1: 6.767 ops/ms
Iteration   2: 6.527 ops/ms
Iteration   3: 6.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.697 ±(99.9%) 2.700 ops/ms [Average]
  (min, avg, max) = (6.527, 6.697, 6.796), stdev = 0.148
  CI (99.9%): [3.997, 9.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.848 ops/ms
# Warmup Iteration   2: 5.563 ops/ms
# Warmup Iteration   3: 6.420 ops/ms
Iteration   1: 6.303 ops/ms
Iteration   2: 6.392 ops/ms
Iteration   3: 6.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.395 ±(99.9%) 1.708 ops/ms [Average]
  (min, avg, max) = (6.303, 6.395, 6.490), stdev = 0.094
  CI (99.9%): [4.687, 8.102] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
# Warmup Iteration   2: 4.990 ops/ms
# Warmup Iteration   3: 5.660 ops/ms
Iteration   1: 5.760 ops/ms
Iteration   2: 5.516 ops/ms
Iteration   3: 5.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.646 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (5.516, 5.646, 5.760), stdev = 0.123
  CI (99.9%): [3.404, 7.888] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.785 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.934 ±(99.9%) 0.015 ms/op
Iteration   1: 5.363 ±(99.9%) 0.007 ms/op
Iteration   2: 4.932 ±(99.9%) 0.010 ms/op
Iteration   3: 5.087 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.128 ±(99.9%) 3.985 ms/op [Average]
  (min, avg, max) = (4.932, 5.128, 5.363), stdev = 0.218
  CI (99.9%): [1.143, 9.113] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.231 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.322 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.008 ms/op
Iteration   1: 4.797 ±(99.9%) 0.016 ms/op
Iteration   2: 4.706 ±(99.9%) 0.009 ms/op
Iteration   3: 5.003 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.835 ±(99.9%) 2.769 ms/op [Average]
  (min, avg, max) = (4.706, 4.835, 5.003), stdev = 0.152
  CI (99.9%): [2.066, 7.604] (assumes normal distribution)


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
# Warmup Iteration   1: 15.921 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.616 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.010 ms/op
Iteration   1: 4.970 ±(99.9%) 0.014 ms/op
Iteration   2: 5.164 ±(99.9%) 0.011 ms/op
Iteration   3: 5.005 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.046 ±(99.9%) 1.887 ms/op [Average]
  (min, avg, max) = (4.970, 5.046, 5.164), stdev = 0.103
  CI (99.9%): [3.159, 6.933] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.760 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.827 ±(99.9%) 0.011 ms/op
Iteration   1: 5.395 ±(99.9%) 0.010 ms/op
Iteration   2: 5.416 ±(99.9%) 0.011 ms/op
Iteration   3: 5.633 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.482 ±(99.9%) 2.408 ms/op [Average]
  (min, avg, max) = (5.395, 5.482, 5.633), stdev = 0.132
  CI (99.9%): [3.074, 7.889] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.067 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 6.287 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.022 ms/op
Iteration   1: 5.110 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.242 ms/op
                 createUser·p0.99:   10.184 ms/op
                 createUser·p0.999:  18.839 ms/op
                 createUser·p0.9999: 25.911 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 4.990 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.078 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 5.084 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  23.103 ms/op
                 createUser·p0.9999: 25.625 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189489
  mean =      5.061 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 110921 
    [ 5.000,  7.500) = 71205 
    [ 7.500, 10.000) = 5096 
    [10.000, 12.500) = 1188 
    [12.500, 15.000) = 433 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =     10.389 ms/op
     p(99.9000) =     21.218 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     28.627 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 14.643 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.248 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.157 ±(99.9%) 0.018 ms/op
Iteration   1: 5.020 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   7.193 ms/op
                 existUser·p0.99:   10.469 ms/op
                 existUser·p0.999:  23.177 ms/op
                 existUser·p0.9999: 32.965 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   2: 4.866 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   6.046 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  25.768 ms/op
                 existUser·p0.9999: 31.351 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 4.891 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.046 ms/op
                 existUser·p0.95:   6.857 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  20.052 ms/op
                 existUser·p0.9999: 29.226 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194725
  mean =      4.925 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 126686 
    [ 5.000,  7.500) = 61314 
    [ 7.500, 10.000) = 4661 
    [10.000, 12.500) = 1155 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     32.999 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 15.705 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.854 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.474 ±(99.9%) 0.023 ms/op
Iteration   1: 5.236 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.531 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.938 ms/op
                 getUser·p0.99:   12.157 ms/op
                 getUser·p0.999:  23.356 ms/op
                 getUser·p0.9999: 31.964 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   2: 4.940 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   7.111 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  18.295 ms/op
                 getUser·p0.9999: 27.821 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 5.194 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.040 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.430 ms/op
                 getUser·p0.99:   10.617 ms/op
                 getUser·p0.999:  24.198 ms/op
                 getUser·p0.9999: 26.406 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 187431
  mean =      5.120 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 113164 
    [ 5.000,  7.500) = 65145 
    [ 7.500, 10.000) = 6547 
    [10.000, 12.500) = 1593 
    [12.500, 15.000) = 537 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     27.616 ms/op
     p(99.9990) =     33.026 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 18.844 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 6.504 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.169 ±(99.9%) 0.027 ms/op
Iteration   1: 6.115 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  27.702 ms/op
                 listUser·p0.9999: 30.576 ms/op
                 listUser·p1.00:   31.785 ms/op

Iteration   2: 5.787 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.925 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 28.130 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   3: 5.938 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   12.042 ms/op
                 listUser·p0.999:  20.286 ms/op
                 listUser·p0.9999: 27.343 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161473
  mean =      5.943 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 38173 
    [ 5.000,  7.500) = 106555 
    [ 7.500, 10.000) = 13529 
    [10.000, 12.500) = 2103 
    [12.500, 15.000) = 577 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.553 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.539 ms/op
     p(99.9000) =     25.299 ms/op
     p(99.9900) =     29.331 ms/op
     p(99.9990) =     31.725 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.284 ± 6.051  ops/ms
ClientPb.existUser                       thrpt       3   6.697 ± 2.700  ops/ms
ClientPb.getUser                         thrpt       3   6.395 ± 1.708  ops/ms
ClientPb.listUser                        thrpt       3   5.646 ± 2.242  ops/ms
ClientPb.createUser                       avgt       3   5.128 ± 3.985   ms/op
ClientPb.existUser                        avgt       3   4.835 ± 2.769   ms/op
ClientPb.getUser                          avgt       3   5.046 ± 1.887   ms/op
ClientPb.listUser                         avgt       3   5.482 ± 2.408   ms/op
ClientPb.createUser                     sample  189489   5.061 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.532           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.439           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.218           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.247           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.803           ms/op
ClientPb.existUser                      sample  194725   4.925 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.986           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.162           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.030           ms/op
ClientPb.getUser                        sample  187431   5.120 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.447           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.748           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.986           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.616           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.227           ms/op
ClientPb.listUser                       sample  161473   5.943 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.539           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.299           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.331           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.785           ms/op
