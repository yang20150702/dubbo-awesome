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
# Warmup Iteration   1: 2.697 ops/ms
# Warmup Iteration   2: 6.348 ops/ms
# Warmup Iteration   3: 9.372 ops/ms
Iteration   1: 9.605 ops/ms
Iteration   2: 9.905 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.936 ±(99.9%) 6.336 ops/ms [Average]
  (min, avg, max) = (9.605, 9.936, 10.298), stdev = 0.347
  CI (99.9%): [3.600, 16.272] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.275 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.405 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.372 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (10.252, 10.372, 10.460), stdev = 0.107
  CI (99.9%): [8.412, 12.333] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 9.075 ops/ms
# Warmup Iteration   3: 9.731 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.021 ±(99.9%) 4.582 ops/ms [Average]
  (min, avg, max) = (9.754, 10.021, 10.253), stdev = 0.251
  CI (99.9%): [5.439, 14.604] (assumes normal distribution)


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
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 7.898 ops/ms
# Warmup Iteration   3: 8.688 ops/ms
Iteration   1: 8.675 ops/ms
Iteration   2: 8.849 ops/ms
Iteration   3: 8.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.753 ±(99.9%) 1.621 ops/ms [Average]
  (min, avg, max) = (8.675, 8.753, 8.849), stdev = 0.089
  CI (99.9%): [7.132, 10.374] (assumes normal distribution)


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
# Warmup Iteration   1: 7.342 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.007 ms/op
Iteration   1: 3.207 ±(99.9%) 0.006 ms/op
Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
Iteration   3: 3.225 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.228 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.207, 3.228, 3.252), stdev = 0.022
  CI (99.9%): [2.818, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 7.501 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.155 ±(99.9%) 0.006 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.057 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.084 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.041, 3.084, 3.155), stdev = 0.061
  CI (99.9%): [1.963, 4.206] (assumes normal distribution)


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
# Warmup Iteration   1: 7.096 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.003 ms/op
Iteration   1: 3.276 ±(99.9%) 0.002 ms/op
Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
Iteration   3: 3.234 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.246 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.229, 3.246, 3.276), stdev = 0.026
  CI (99.9%): [2.774, 3.719] (assumes normal distribution)


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
# Warmup Iteration   1: 9.643 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.003 ms/op
Iteration   1: 3.777 ±(99.9%) 0.008 ms/op
Iteration   2: 3.735 ±(99.9%) 0.009 ms/op
Iteration   3: 3.695 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.736 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (3.695, 3.736, 3.777), stdev = 0.041
  CI (99.9%): [2.989, 4.483] (assumes normal distribution)


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
# Warmup Iteration   1: 8.201 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.009 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.683 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 19.622 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  12.501 ms/op
                 createUser·p0.9999: 20.180 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 23.914 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304159
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15950 
    [ 2.500,  5.000) = 282870 
    [ 5.000,  7.500) = 4459 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.467 ms/op
     p(99.9000) =     11.117 ms/op
     p(99.9900) =     21.993 ms/op
     p(99.9990) =     24.213 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 6.612 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.009 ms/op
Iteration   1: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  8.329 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 24.244 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  15.585 ms/op
                 existUser·p0.9999: 21.941 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305082
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14120 
    [ 2.500,  5.000) = 285309 
    [ 5.000,  7.500) = 5024 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.506 ms/op
     p(99.9000) =     14.899 ms/op
     p(99.9900) =     23.132 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 7.643 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.010 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  17.203 ms/op
                 getUser·p0.9999: 20.802 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  19.104 ms/op
                 getUser·p0.9999: 27.729 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 20.993 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302262
  mean =      3.173 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14397 
    [ 2.500,  5.000) = 282577 
    [ 5.000,  7.500) = 4397 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.516 ms/op
     p(99.9900) =     26.028 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 8.975 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.011 ms/op
Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.688 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 14.539 ms/op
                 listUser·p1.00:   16.581 ms/op

Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.501 ms/op
                 listUser·p0.9999: 16.997 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254587
  mean =      3.770 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 244761 
    [ 5.000,  7.500) = 7634 
    [ 7.500, 10.000) = 1482 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     13.868 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.936 ± 6.336  ops/ms
ClientPb.existUser                       thrpt       3  10.372 ± 1.961  ops/ms
ClientPb.getUser                         thrpt       3  10.021 ± 4.582  ops/ms
ClientPb.listUser                        thrpt       3   8.753 ± 1.621  ops/ms
ClientPb.createUser                       avgt       3   3.228 ± 0.410   ms/op
ClientPb.existUser                        avgt       3   3.084 ± 1.122   ms/op
ClientPb.getUser                          avgt       3   3.246 ± 0.473   ms/op
ClientPb.listUser                         avgt       3   3.736 ± 0.747   ms/op
ClientPb.createUser                     sample  304159   3.158 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.467           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.642           ms/op
ClientPb.existUser                      sample  305082   3.143 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.974           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.506           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.899           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.132           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.805           ms/op
ClientPb.getUser                        sample  302262   3.173 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.934           ms/op
ClientPb.listUser                       sample  254587   3.770 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.868           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.087           ms/op
