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
# Warmup Iteration   1: 2.069 ops/ms
# Warmup Iteration   2: 5.079 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 9.106 ops/ms
Iteration   2: 9.075 ops/ms
Iteration   3: 9.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.219 ±(99.9%) 4.053 ops/ms [Average]
  (min, avg, max) = (9.075, 9.219, 9.475), stdev = 0.222
  CI (99.9%): [5.165, 13.272] (assumes normal distribution)


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
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 8.187 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 9.401 ops/ms
Iteration   2: 9.624 ops/ms
Iteration   3: 9.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.616 ±(99.9%) 3.852 ops/ms [Average]
  (min, avg, max) = (9.401, 9.616, 9.823), stdev = 0.211
  CI (99.9%): [5.764, 13.469] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.033 ops/ms
# Warmup Iteration   2: 8.575 ops/ms
# Warmup Iteration   3: 9.064 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.403 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (9.344, 9.403, 9.456), stdev = 0.056
  CI (99.9%): [8.381, 10.424] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.696 ops/ms
# Warmup Iteration   2: 7.356 ops/ms
# Warmup Iteration   3: 7.611 ops/ms
Iteration   1: 7.911 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.969 ±(99.9%) 4.705 ops/ms [Average]
  (min, avg, max) = (7.745, 7.969, 8.251), stdev = 0.258
  CI (99.9%): [3.263, 12.674] (assumes normal distribution)


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
# Warmup Iteration   1: 10.057 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.008 ms/op
Iteration   1: 3.478 ±(99.9%) 0.004 ms/op
Iteration   2: 3.388 ±(99.9%) 0.007 ms/op
Iteration   3: 3.323 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.396 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (3.323, 3.396, 3.478), stdev = 0.078
  CI (99.9%): [1.981, 4.811] (assumes normal distribution)


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
# Warmup Iteration   1: 8.214 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.004 ms/op
Iteration   1: 3.340 ±(99.9%) 0.005 ms/op
Iteration   2: 3.271 ±(99.9%) 0.006 ms/op
Iteration   3: 3.388 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.271, 3.333, 3.388), stdev = 0.059
  CI (99.9%): [2.258, 4.407] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.564 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.006 ms/op
Iteration   1: 3.499 ±(99.9%) 0.007 ms/op
Iteration   2: 3.402 ±(99.9%) 0.005 ms/op
Iteration   3: 3.500 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.402, 3.467, 3.500), stdev = 0.056
  CI (99.9%): [2.439, 4.495] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.456 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.010 ms/op
Iteration   1: 3.941 ±(99.9%) 0.009 ms/op
Iteration   2: 3.895 ±(99.9%) 0.013 ms/op
Iteration   3: 3.968 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.935 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.895, 3.935, 3.968), stdev = 0.037
  CI (99.9%): [3.256, 4.613] (assumes normal distribution)


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
# Warmup Iteration   1: 9.665 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
Iteration   1: 3.490 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  21.147 ms/op
                 createUser·p0.9999: 26.728 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 3.477 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  22.907 ms/op
                 createUser·p0.9999: 25.704 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 3.606 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  20.823 ms/op
                 createUser·p0.9999: 25.105 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272284
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11216 
    [ 2.500,  5.000) = 249452 
    [ 5.000,  7.500) = 10309 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 161 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     21.028 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     27.150 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 8.976 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  20.194 ms/op
                 existUser·p0.9999: 24.818 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.398 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  24.509 ms/op
                 existUser·p0.9999: 26.824 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.333 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  20.515 ms/op
                 existUser·p0.9999: 28.685 ms/op
                 existUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286000
  mean =      3.353 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11825 
    [ 2.500,  5.000) = 266884 
    [ 5.000,  7.500) = 6004 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 123 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     27.355 ms/op
     p(99.9990) =     28.859 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 9.431 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.013 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  21.468 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  24.436 ms/op
                 getUser·p0.9999: 31.813 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  20.701 ms/op
                 getUser·p0.9999: 32.656 ms/op
                 getUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278121
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8694 
    [ 2.500,  5.000) = 262412 
    [ 5.000,  7.500) = 6022 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     21.426 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     33.743 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 11.013 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.532 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
Iteration   1: 4.050 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.536 ms/op
                 listUser·p0.999:  24.139 ms/op
                 listUser·p0.9999: 33.456 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   2: 4.108 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 23.534 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.035 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.368 ms/op
                 listUser·p0.999:  15.954 ms/op
                 listUser·p0.9999: 18.582 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236276
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 226290 
    [ 5.000,  7.500) = 7639 
    [ 7.500, 10.000) = 1394 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     17.915 ms/op
     p(99.9900) =     33.227 ms/op
     p(99.9990) =     33.477 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.219 ± 4.053  ops/ms
ClientPb.existUser                       thrpt       3   9.616 ± 3.852  ops/ms
ClientPb.getUser                         thrpt       3   9.403 ± 1.021  ops/ms
ClientPb.listUser                        thrpt       3   7.969 ± 4.705  ops/ms
ClientPb.createUser                       avgt       3   3.396 ± 1.415   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 1.075   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 1.028   ms/op
ClientPb.listUser                         avgt       3   3.935 ± 0.679   ms/op
ClientPb.createUser                     sample  272284   3.523 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.018           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.525           ms/op
ClientPb.existUser                      sample  286000   3.353 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.974           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.021           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.355           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  278121   3.449 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.415           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.426           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.982           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  236276   4.064 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.915           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.227           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.686           ms/op
