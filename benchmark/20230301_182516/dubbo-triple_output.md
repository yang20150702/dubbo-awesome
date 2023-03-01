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
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 5.865 ops/ms
# Warmup Iteration   3: 9.319 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.617 ±(99.9%) 3.957 ops/ms [Average]
  (min, avg, max) = (9.372, 9.617, 9.786), stdev = 0.217
  CI (99.9%): [5.660, 13.574] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 9.830 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 9.748 ops/ms
Iteration   3: 10.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.870 ±(99.9%) 3.091 ops/ms [Average]
  (min, avg, max) = (9.748, 9.870, 10.064), stdev = 0.169
  CI (99.9%): [6.779, 12.961] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 9.606 ops/ms
Iteration   2: 9.582 ops/ms
Iteration   3: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.613 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (9.582, 9.613, 9.652), stdev = 0.036
  CI (99.9%): [8.958, 10.268] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 8.411 ops/ms
Iteration   3: 8.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.277 ±(99.9%) 3.293 ops/ms [Average]
  (min, avg, max) = (8.072, 8.277, 8.411), stdev = 0.181
  CI (99.9%): [4.984, 11.570] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.542 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.003 ms/op
Iteration   1: 3.254 ±(99.9%) 0.003 ms/op
Iteration   2: 3.192 ±(99.9%) 0.002 ms/op
Iteration   3: 3.278 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.241 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.192, 3.241, 3.278), stdev = 0.044
  CI (99.9%): [2.434, 4.049] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.005 ms/op
Iteration   1: 3.203 ±(99.9%) 0.004 ms/op
Iteration   2: 3.253 ±(99.9%) 0.004 ms/op
Iteration   3: 3.147 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.201 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.147, 3.201, 3.253), stdev = 0.053
  CI (99.9%): [2.227, 4.175] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.949 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.004 ms/op
Iteration   1: 3.225 ±(99.9%) 0.005 ms/op
Iteration   2: 3.262 ±(99.9%) 0.003 ms/op
Iteration   3: 3.295 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.261 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.225, 3.261, 3.295), stdev = 0.035
  CI (99.9%): [2.626, 3.895] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.343 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.008 ms/op
Iteration   1: 3.822 ±(99.9%) 0.009 ms/op
Iteration   2: 3.781 ±(99.9%) 0.008 ms/op
Iteration   3: 3.659 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.754 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (3.659, 3.754, 3.822), stdev = 0.085
  CI (99.9%): [2.212, 5.296] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.922 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
Iteration   1: 3.208 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 20.514 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  15.855 ms/op
                 createUser·p0.9999: 22.259 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  19.674 ms/op
                 createUser·p0.9999: 23.147 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296797
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15454 
    [ 2.500,  5.000) = 276417 
    [ 5.000,  7.500) = 3757 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 191 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.413 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.914 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 22.948 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.250 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  12.185 ms/op
                 existUser·p0.9999: 25.254 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 27.060 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297151
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16806 
    [ 2.500,  5.000) = 275014 
    [ 5.000,  7.500) = 4336 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.508 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.011 ms/op
Iteration   1: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  17.667 ms/op
                 getUser·p0.9999: 22.165 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  20.759 ms/op
                 getUser·p0.9999: 29.688 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 32.384 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284969
  mean =      3.366 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13425 
    [ 2.500,  5.000) = 264133 
    [ 5.000,  7.500) = 5889 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     17.664 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     32.699 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.607 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
Iteration   1: 3.929 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.424 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  18.205 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.814 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 15.853 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 19.721 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246782
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 238564 
    [ 5.000,  7.500) = 5662 
    [ 7.500, 10.000) = 1771 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.924 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.617 ± 3.957  ops/ms
ClientPb.existUser                       thrpt       3   9.870 ± 3.091  ops/ms
ClientPb.getUser                         thrpt       3   9.613 ± 0.655  ops/ms
ClientPb.listUser                        thrpt       3   8.277 ± 3.293  ops/ms
ClientPb.createUser                       avgt       3   3.241 ± 0.808   ms/op
ClientPb.existUser                        avgt       3   3.201 ± 0.974   ms/op
ClientPb.getUser                          avgt       3   3.261 ± 0.634   ms/op
ClientPb.listUser                         avgt       3   3.754 ± 1.542   ms/op
ClientPb.createUser                     sample  296797   3.231 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.321           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.625           ms/op
ClientPb.existUser                      sample  297151   3.226 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.440           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  284969   3.366 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.268           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.664           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.540           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.096           ms/op
ClientPb.listUser                       sample  246782   3.888 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.424           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
