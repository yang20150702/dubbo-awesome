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
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 5.661 ops/ms
# Warmup Iteration   3: 8.738 ops/ms
Iteration   1: 9.570 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 9.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.797 ±(99.9%) 6.745 ops/ms [Average]
  (min, avg, max) = (9.570, 9.797, 10.224), stdev = 0.370
  CI (99.9%): [3.052, 16.542] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 9.807 ops/ms
Iteration   1: 9.668 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.956 ±(99.9%) 4.578 ops/ms [Average]
  (min, avg, max) = (9.668, 9.956, 10.126), stdev = 0.251
  CI (99.9%): [5.378, 14.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ops/ms
# Warmup Iteration   2: 9.099 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 10.293 ops/ms
Iteration   2: 9.719 ops/ms
Iteration   3: 10.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.083 ±(99.9%) 5.770 ops/ms [Average]
  (min, avg, max) = (9.719, 10.083, 10.293), stdev = 0.316
  CI (99.9%): [4.313, 15.853] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 7.509 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.814 ops/ms
Iteration   2: 8.404 ops/ms
Iteration   3: 8.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.288 ±(99.9%) 7.823 ops/ms [Average]
  (min, avg, max) = (7.814, 8.288, 8.648), stdev = 0.429
  CI (99.9%): [0.466, 16.111] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.317 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.006 ms/op
Iteration   1: 3.322 ±(99.9%) 0.008 ms/op
Iteration   2: 3.231 ±(99.9%) 0.005 ms/op
Iteration   3: 3.199 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.251 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.199, 3.251, 3.322), stdev = 0.064
  CI (99.9%): [2.085, 4.416] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.694 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.003 ms/op
Iteration   1: 3.235 ±(99.9%) 0.004 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 3.077 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.117 ±(99.9%) 1.893 ms/op [Average]
  (min, avg, max) = (3.039, 3.117, 3.235), stdev = 0.104
  CI (99.9%): [1.224, 5.009] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.913 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.002 ms/op
Iteration   1: 3.287 ±(99.9%) 0.005 ms/op
Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
Iteration   3: 3.172 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.185 ±(99.9%) 1.748 ms/op [Average]
  (min, avg, max) = (3.097, 3.185, 3.287), stdev = 0.096
  CI (99.9%): [1.437, 4.933] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.761 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.005 ms/op
Iteration   1: 3.712 ±(99.9%) 0.010 ms/op
Iteration   2: 3.879 ±(99.9%) 0.006 ms/op
Iteration   3: 3.801 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.798 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (3.712, 3.798, 3.879), stdev = 0.084
  CI (99.9%): [2.269, 5.326] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.631 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
Iteration   1: 3.271 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  17.512 ms/op
                 createUser·p0.9999: 21.496 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.210 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  21.203 ms/op
                 createUser·p0.9999: 28.378 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  16.258 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293973
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13489 
    [ 2.500,  5.000) = 274760 
    [ 5.000,  7.500) = 4536 
    [ 7.500, 10.000) = 676 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     17.499 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.713 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.950 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 20.831 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  10.543 ms/op
                 existUser·p0.9999: 22.798 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.287 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  10.461 ms/op
                 existUser·p0.9999: 32.318 ms/op
                 existUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302783
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16501 
    [ 2.500,  5.000) = 279762 
    [ 5.000,  7.500) = 5693 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.881 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     32.964 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.011 ms/op
Iteration   1: 3.399 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  18.111 ms/op
                 getUser·p0.9999: 20.283 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  11.899 ms/op
                 getUser·p0.9999: 23.619 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  12.109 ms/op
                 getUser·p0.9999: 24.351 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294481
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9661 
    [ 2.500,  5.000) = 278931 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     11.936 ms/op
     p(99.9900) =     23.760 ms/op
     p(99.9990) =     25.111 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 9.727 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.014 ms/op
Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.657 ms/op
                 listUser·p0.999:  18.631 ms/op
                 listUser·p0.9999: 24.568 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.248 ms/op
                 listUser·p0.9999: 23.524 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.674 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 21.066 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242837
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 232101 
    [ 5.000,  7.500) = 8071 
    [ 7.500, 10.000) = 1823 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.640 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     23.682 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.797 ± 6.745  ops/ms
ClientPb.existUser                       thrpt       3   9.956 ± 4.578  ops/ms
ClientPb.getUser                         thrpt       3  10.083 ± 5.770  ops/ms
ClientPb.listUser                        thrpt       3   8.288 ± 7.823  ops/ms
ClientPb.createUser                       avgt       3   3.251 ± 1.166   ms/op
ClientPb.existUser                        avgt       3   3.117 ± 1.893   ms/op
ClientPb.getUser                          avgt       3   3.185 ± 1.748   ms/op
ClientPb.listUser                         avgt       3   3.798 ± 1.528   ms/op
ClientPb.createUser                     sample  293973   3.267 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.106           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.499           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.673           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  302783   3.168 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.837           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.867           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.292           ms/op
ClientPb.getUser                        sample  294481   3.258 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.776           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.936           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.760           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.494           ms/op
ClientPb.listUser                       sample  242837   3.951 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.640           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.969           ms/op
