# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 4.974 ops/ms
# Warmup Iteration   3: 8.476 ops/ms
Iteration   1: 9.384 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.311 ±(99.9%) 7.622 ops/ms [Average]
  (min, avg, max) = (8.861, 9.311, 9.687), stdev = 0.418
  CI (99.9%): [1.689, 16.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 8.738 ops/ms
# Warmup Iteration   3: 9.559 ops/ms
Iteration   1: 10.118 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 9.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.026 ±(99.9%) 2.454 ops/ms [Average]
  (min, avg, max) = (9.872, 10.026, 10.118), stdev = 0.135
  CI (99.9%): [7.572, 12.481] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 8.538 ops/ms
# Warmup Iteration   3: 9.086 ops/ms
Iteration   1: 9.180 ops/ms
Iteration   2: 9.203 ops/ms
Iteration   3: 9.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.293 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (9.180, 9.293, 9.496), stdev = 0.176
  CI (99.9%): [6.080, 12.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.721 ops/ms
# Warmup Iteration   2: 7.149 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 8.106 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 8.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.196 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (8.106, 8.196, 8.302), stdev = 0.099
  CI (99.9%): [6.388, 10.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.397 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.006 ms/op
Iteration   1: 3.517 ±(99.9%) 0.007 ms/op
Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
Iteration   3: 3.304 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.410 ±(99.9%) 1.941 ms/op [Average]
  (min, avg, max) = (3.304, 3.410, 3.517), stdev = 0.106
  CI (99.9%): [1.469, 5.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.910 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
Iteration   2: 3.199 ±(99.9%) 0.006 ms/op
Iteration   3: 3.248 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.238 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.199, 3.238, 3.266), stdev = 0.035
  CI (99.9%): [2.602, 3.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.604 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.005 ms/op
Iteration   1: 3.389 ±(99.9%) 0.007 ms/op
Iteration   2: 3.389 ±(99.9%) 0.006 ms/op
Iteration   3: 3.378 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.385 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (3.378, 3.385, 3.389), stdev = 0.006
  CI (99.9%): [3.274, 3.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.328 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.948 ±(99.9%) 0.017 ms/op
Iteration   2: 3.919 ±(99.9%) 0.014 ms/op
Iteration   3: 3.835 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.901 ±(99.9%) 1.071 ms/op [Average]
  (min, avg, max) = (3.835, 3.901, 3.948), stdev = 0.059
  CI (99.9%): [2.830, 4.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.167 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.011 ms/op
Iteration   1: 3.320 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.947 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  15.059 ms/op
                 createUser·p0.9999: 23.359 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  22.120 ms/op
                 createUser·p0.9999: 27.863 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  19.729 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284006
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8330 
    [ 2.500,  5.000) = 269906 
    [ 5.000,  7.500) = 4862 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     28.036 ms/op
     p(99.9990) =     30.337 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.398 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  8.159 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  21.496 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  23.298 ms/op
                 existUser·p0.9999: 27.217 ms/op
                 existUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286178
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15381 
    [ 2.500,  5.000) = 265605 
    [ 5.000,  7.500) = 4651 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     25.322 ms/op
     p(99.9990) =     27.956 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.469 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.012 ms/op
Iteration   1: 3.566 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  13.320 ms/op
                 getUser·p0.9999: 22.414 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.483 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  22.234 ms/op
                 getUser·p0.9999: 25.586 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.536 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  20.428 ms/op
                 getUser·p0.9999: 30.800 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272129
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10125 
    [ 2.500,  5.000) = 250621 
    [ 5.000,  7.500) = 9886 
    [ 7.500, 10.000) = 1077 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.433 ms/op
     p(99.9900) =     29.943 ms/op
     p(99.9990) =     31.050 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.092 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.013 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  20.841 ms/op
                 listUser·p0.9999: 24.317 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.578 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 17.820 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240057
  mean =      3.997 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 231494 
    [ 5.000,  7.500) = 5939 
    [ 7.500, 10.000) = 1706 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     24.727 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.311 ± 7.622  ops/ms
ClientPb.existUser                       thrpt       3  10.026 ± 2.454  ops/ms
ClientPb.getUser                         thrpt       3   9.293 ± 3.213  ops/ms
ClientPb.listUser                        thrpt       3   8.196 ± 1.808  ops/ms
ClientPb.createUser                       avgt       3   3.410 ± 1.941   ms/op
ClientPb.existUser                        avgt       3   3.238 ± 0.636   ms/op
ClientPb.getUser                          avgt       3   3.385 ± 0.111   ms/op
ClientPb.listUser                         avgt       3   3.901 ± 1.071   ms/op
ClientPb.createUser                     sample  284006   3.379 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.366           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.036           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.818           ms/op
ClientPb.existUser                      sample  286178   3.353 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.167           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.191           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.322           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.803           ms/op
ClientPb.getUser                        sample  272129   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  240057   3.997 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.452           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.728           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
