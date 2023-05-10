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
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 5.942 ops/ms
# Warmup Iteration   3: 9.068 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.251 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.036 ±(99.9%) 3.432 ops/ms [Average]
  (min, avg, max) = (9.902, 10.036, 10.251), stdev = 0.188
  CI (99.9%): [6.605, 13.468] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ops/ms
# Warmup Iteration   2: 9.450 ops/ms
# Warmup Iteration   3: 10.037 ops/ms
Iteration   1: 10.346 ops/ms
Iteration   2: 10.618 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.539 ±(99.9%) 3.067 ops/ms [Average]
  (min, avg, max) = (10.346, 10.539, 10.654), stdev = 0.168
  CI (99.9%): [7.473, 13.606] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.179 ops/ms
# Warmup Iteration   2: 8.730 ops/ms
# Warmup Iteration   3: 9.981 ops/ms
Iteration   1: 9.984 ops/ms
Iteration   2: 10.262 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.126 ±(99.9%) 2.536 ops/ms [Average]
  (min, avg, max) = (9.984, 10.126, 10.262), stdev = 0.139
  CI (99.9%): [7.590, 12.663] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 7.421 ops/ms
# Warmup Iteration   3: 8.471 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 8.640 ops/ms
Iteration   3: 8.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 0.679 ops/ms [Average]
  (min, avg, max) = (8.567, 8.599, 8.640), stdev = 0.037
  CI (99.9%): [7.920, 9.278] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.448 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.003 ms/op
Iteration   1: 3.306 ±(99.9%) 0.005 ms/op
Iteration   2: 3.328 ±(99.9%) 0.003 ms/op
Iteration   3: 3.258 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.298 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.258, 3.298, 3.328), stdev = 0.036
  CI (99.9%): [2.645, 3.950] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.300 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.002 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.058 ±(99.9%) 1.658 ms/op [Average]
  (min, avg, max) = (2.970, 3.058, 3.152), stdev = 0.091
  CI (99.9%): [1.399, 4.716] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.812 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.003 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
Iteration   3: 3.234 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.150 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (3.107, 3.150, 3.234), stdev = 0.073
  CI (99.9%): [1.815, 4.485] (assumes normal distribution)


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
# Warmup Iteration   1: 8.684 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.008 ms/op
Iteration   1: 3.722 ±(99.9%) 0.008 ms/op
Iteration   2: 3.718 ±(99.9%) 0.011 ms/op
Iteration   3: 3.675 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.675, 3.705, 3.722), stdev = 0.026
  CI (99.9%): [3.234, 4.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.850 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.012 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.901 ms/op
                 createUser·p0.999:  17.282 ms/op
                 createUser·p0.9999: 21.847 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  17.336 ms/op
                 createUser·p0.9999: 23.704 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  15.121 ms/op
                 createUser·p0.9999: 21.892 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291387
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18438 
    [ 2.500,  5.000) = 266090 
    [ 5.000,  7.500) = 5762 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     15.149 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.409 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
Iteration   1: 3.096 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  13.135 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  11.569 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  12.671 ms/op
                 existUser·p0.9999: 20.190 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304752
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19676 
    [ 2.500,  5.000) = 279469 
    [ 5.000,  7.500) = 4903 
    [ 7.500, 10.000) = 298 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.934 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     12.898 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.741 ms/op
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
# Warmup Iteration   1: 8.193 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.010 ms/op
Iteration   1: 3.427 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 20.698 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.494 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  10.148 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296526
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10703 
    [ 2.500,  5.000) = 277774 
    [ 5.000,  7.500) = 6783 
    [ 7.500, 10.000) = 772 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.326 ms/op
     p(99.9900) =     23.178 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 8.924 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.011 ms/op
Iteration   1: 3.749 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 20.657 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.718 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.722 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.125 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257314
  mean =      3.730 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 249773 
    [ 5.000,  7.500) = 5738 
    [ 7.500, 10.000) = 1094 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.085 ms/op
     p(99.9900) =     20.539 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.036 ± 3.432  ops/ms
ClientPb.existUser                       thrpt       3  10.539 ± 3.067  ops/ms
ClientPb.getUser                         thrpt       3  10.126 ± 2.536  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 0.679  ops/ms
ClientPb.createUser                       avgt       3   3.298 ± 0.652   ms/op
ClientPb.existUser                        avgt       3   3.058 ± 1.658   ms/op
ClientPb.getUser                          avgt       3   3.150 ± 1.335   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 0.471   ms/op
ClientPb.createUser                     sample  291387   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.932           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.149           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.610           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.264           ms/op
ClientPb.existUser                      sample  304752   3.148 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.822           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.934           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.898           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.855           ms/op
ClientPb.getUser                        sample  296526   3.235 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.092           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.326           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.178           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.183           ms/op
ClientPb.listUser                       sample  257314   3.730 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.085           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.539           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.529           ms/op
