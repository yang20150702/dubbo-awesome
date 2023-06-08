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
# Warmup Iteration   1: 2.335 ops/ms
# Warmup Iteration   2: 5.557 ops/ms
# Warmup Iteration   3: 9.058 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 9.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.929 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (9.864, 9.929, 9.966), stdev = 0.056
  CI (99.9%): [8.899, 10.960] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 9.263 ops/ms
# Warmup Iteration   3: 10.006 ops/ms
Iteration   1: 10.242 ops/ms
Iteration   2: 10.041 ops/ms
Iteration   3: 9.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.058 ±(99.9%) 3.211 ops/ms [Average]
  (min, avg, max) = (9.892, 10.058, 10.242), stdev = 0.176
  CI (99.9%): [6.847, 13.269] (assumes normal distribution)


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
# Warmup Iteration   1: 3.107 ops/ms
# Warmup Iteration   2: 8.238 ops/ms
# Warmup Iteration   3: 9.538 ops/ms
Iteration   1: 9.631 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 9.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.764 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (9.631, 9.764, 9.838), stdev = 0.115
  CI (99.9%): [7.664, 11.864] (assumes normal distribution)


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
# Warmup Iteration   1: 3.055 ops/ms
# Warmup Iteration   2: 7.349 ops/ms
# Warmup Iteration   3: 8.174 ops/ms
Iteration   1: 8.208 ops/ms
Iteration   2: 8.435 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.274 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (8.177, 8.274, 8.435), stdev = 0.141
  CI (99.9%): [5.704, 10.843] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.238 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.004 ms/op
Iteration   1: 3.173 ±(99.9%) 0.003 ms/op
Iteration   2: 3.333 ±(99.9%) 0.005 ms/op
Iteration   3: 3.320 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.275 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (3.173, 3.275, 3.333), stdev = 0.089
  CI (99.9%): [1.657, 4.893] (assumes normal distribution)


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
# Warmup Iteration   1: 8.956 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.004 ms/op
Iteration   1: 3.153 ±(99.9%) 0.003 ms/op
Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
Iteration   3: 3.189 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.143 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.087, 3.143, 3.189), stdev = 0.052
  CI (99.9%): [2.194, 4.092] (assumes normal distribution)


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
# Warmup Iteration   1: 8.447 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.006 ms/op
Iteration   1: 3.270 ±(99.9%) 0.006 ms/op
Iteration   2: 3.298 ±(99.9%) 0.004 ms/op
Iteration   3: 3.385 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.317 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.270, 3.317, 3.385), stdev = 0.060
  CI (99.9%): [2.229, 4.406] (assumes normal distribution)


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
# Warmup Iteration   1: 10.849 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.003 ms/op
Iteration   1: 3.909 ±(99.9%) 0.007 ms/op
Iteration   2: 3.763 ±(99.9%) 0.008 ms/op
Iteration   3: 3.763 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.812 ±(99.9%) 1.533 ms/op [Average]
  (min, avg, max) = (3.763, 3.812, 3.909), stdev = 0.084
  CI (99.9%): [2.278, 5.345] (assumes normal distribution)


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
# Warmup Iteration   1: 8.091 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
Iteration   1: 3.227 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  19.567 ms/op
                 createUser·p0.9999: 22.853 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  15.230 ms/op
                 createUser·p0.9999: 20.039 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292470
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14031 
    [ 2.500,  5.000) = 270989 
    [ 5.000,  7.500) = 6186 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     16.425 ms/op
     p(99.9900) =     22.504 ms/op
     p(99.9990) =     22.980 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 7.546 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
Iteration   1: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.572 ms/op
                 existUser·p0.9999: 21.627 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.302 ms/op
                 existUser·p0.9999: 22.729 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  13.426 ms/op
                 existUser·p0.9999: 22.678 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307888
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13439 
    [ 2.500,  5.000) = 289027 
    [ 5.000,  7.500) = 4452 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.656 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 8.446 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.013 ms/op
Iteration   1: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  15.811 ms/op
                 getUser·p0.9999: 21.704 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.157 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  13.661 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  13.953 ms/op
                 getUser·p0.9999: 21.692 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295813
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12433 
    [ 2.500,  5.000) = 276780 
    [ 5.000,  7.500) = 5555 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 185 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.084 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.308 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 10.387 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.013 ms/op
Iteration   1: 3.797 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 22.910 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.799 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 14.565 ms/op
                 listUser·p1.00:   15.335 ms/op

Iteration   3: 3.943 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 15.892 ms/op
                 listUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249398
  mean =      3.845 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 242129 
    [ 5.000,  7.500) = 5370 
    [ 7.500, 10.000) = 1229 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.936 ms/op
     p(99.9900) =     20.217 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.929 ± 1.031  ops/ms
ClientPb.existUser                       thrpt       3  10.058 ± 3.211  ops/ms
ClientPb.getUser                         thrpt       3   9.764 ± 2.100  ops/ms
ClientPb.listUser                        thrpt       3   8.274 ± 2.570  ops/ms
ClientPb.createUser                       avgt       3   3.275 ± 1.618   ms/op
ClientPb.existUser                        avgt       3   3.143 ± 0.949   ms/op
ClientPb.getUser                          avgt       3   3.317 ± 1.089   ms/op
ClientPb.listUser                         avgt       3   3.812 ± 1.533   ms/op
ClientPb.createUser                     sample  292470   3.279 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.425           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.504           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.263           ms/op
ClientPb.existUser                      sample  307888   3.118 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.018           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.479           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.855           ms/op
ClientPb.getUser                        sample  295813   3.242 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.084           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.167           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559           ms/op
ClientPb.listUser                       sample  249398   3.845 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.350           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.936           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.217           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233           ms/op
