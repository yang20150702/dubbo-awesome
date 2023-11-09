# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.173 ops/ms
# Warmup Iteration   2: 5.486 ops/ms
# Warmup Iteration   3: 8.347 ops/ms
Iteration   1: 8.859 ops/ms
Iteration   2: 9.049 ops/ms
Iteration   3: 9.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.979 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (8.859, 8.979, 9.049), stdev = 0.104
  CI (99.9%): [7.078, 10.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 8.177 ops/ms
# Warmup Iteration   3: 9.779 ops/ms
Iteration   1: 9.777 ops/ms
Iteration   2: 9.704 ops/ms
Iteration   3: 9.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.764 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (9.704, 9.764, 9.811), stdev = 0.055
  CI (99.9%): [8.759, 10.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.838 ops/ms
# Warmup Iteration   2: 8.290 ops/ms
# Warmup Iteration   3: 8.675 ops/ms
Iteration   1: 9.252 ops/ms
Iteration   2: 9.243 ops/ms
Iteration   3: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.197 ±(99.9%) 1.598 ops/ms [Average]
  (min, avg, max) = (9.096, 9.197, 9.252), stdev = 0.088
  CI (99.9%): [7.599, 10.795] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.424 ops/ms
# Warmup Iteration   2: 7.195 ops/ms
# Warmup Iteration   3: 7.548 ops/ms
Iteration   1: 7.601 ops/ms
Iteration   2: 7.498 ops/ms
Iteration   3: 7.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.588 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (7.498, 7.588, 7.666), stdev = 0.085
  CI (99.9%): [6.042, 9.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.433 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.003 ms/op
Iteration   1: 3.520 ±(99.9%) 0.004 ms/op
Iteration   2: 3.448 ±(99.9%) 0.003 ms/op
Iteration   3: 3.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.499 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.448, 3.499, 3.528), stdev = 0.044
  CI (99.9%): [2.692, 4.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.141 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.004 ms/op
Iteration   1: 3.384 ±(99.9%) 0.004 ms/op
Iteration   2: 3.341 ±(99.9%) 0.003 ms/op
Iteration   3: 3.360 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.362 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.341, 3.362, 3.384), stdev = 0.022
  CI (99.9%): [2.962, 3.761] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.374 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.005 ms/op
Iteration   1: 3.511 ±(99.9%) 0.005 ms/op
Iteration   2: 3.483 ±(99.9%) 0.005 ms/op
Iteration   3: 3.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.484 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.458, 3.484, 3.511), stdev = 0.027
  CI (99.9%): [2.994, 3.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.102 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.006 ms/op
Iteration   1: 4.227 ±(99.9%) 0.006 ms/op
Iteration   2: 4.214 ±(99.9%) 0.008 ms/op
Iteration   3: 4.232 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.224 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (4.214, 4.224, 4.232), stdev = 0.009
  CI (99.9%): [4.057, 4.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.770 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.014 ms/op
Iteration   1: 3.575 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  20.808 ms/op
                 createUser·p0.9999: 25.372 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 3.520 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  21.829 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  21.365 ms/op
                 createUser·p0.9999: 26.880 ms/op
                 createUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272011
  mean =      3.526 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4269 
    [ 2.500,  5.000) = 262701 
    [ 5.000,  7.500) = 3732 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.889 ms/op
     p(99.9000) =     21.298 ms/op
     p(99.9900) =     25.644 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.027 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.008 ms/op
Iteration   1: 3.306 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  16.182 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.490 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  22.053 ms/op
                 existUser·p0.9999: 25.576 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.855 ms/op
                 existUser·p0.999:  19.726 ms/op
                 existUser·p0.9999: 26.182 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282356
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8860 
    [ 2.500,  5.000) = 266974 
    [ 5.000,  7.500) = 5085 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 171 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     25.453 ms/op
     p(99.9990) =     26.810 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.578 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.012 ms/op
Iteration   1: 3.619 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  14.696 ms/op
                 getUser·p0.9999: 20.485 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 3.466 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.102 ms/op
                 getUser·p0.999:  19.058 ms/op
                 getUser·p0.9999: 21.613 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 3.582 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.574 ms/op
                 getUser·p0.999:  16.867 ms/op
                 getUser·p0.9999: 24.611 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269846
  mean =      3.555 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2710 
    [ 2.500,  5.000) = 261257 
    [ 5.000,  7.500) = 4566 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     23.692 ms/op
     p(99.9990) =     24.822 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.700 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.014 ms/op
Iteration   1: 4.286 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  20.441 ms/op
                 listUser·p0.9999: 25.365 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.211 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.985 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 15.981 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   3: 4.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  14.528 ms/op
                 listUser·p0.9999: 16.382 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228800
  mean =      4.192 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 219676 
    [ 5.000,  7.500) = 7269 
    [ 7.500, 10.000) = 1076 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.071 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     24.227 ms/op
     p(99.9990) =     25.868 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.979 ± 1.901  ops/ms
ClientPb.existUser                       thrpt       3   9.764 ± 1.005  ops/ms
ClientPb.getUser                         thrpt       3   9.197 ± 1.598  ops/ms
ClientPb.listUser                        thrpt       3   7.588 ± 1.546  ops/ms
ClientPb.createUser                       avgt       3   3.499 ± 0.807   ms/op
ClientPb.existUser                        avgt       3   3.362 ± 0.399   ms/op
ClientPb.getUser                          avgt       3   3.484 ± 0.490   ms/op
ClientPb.listUser                         avgt       3   4.224 ± 0.168   ms/op
ClientPb.createUser                     sample  272011   3.526 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.849           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.889           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.644           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.558           ms/op
ClientPb.existUser                      sample  282356   3.399 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.621           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.447           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.453           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  269846   3.555 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.280           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.713           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.692           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.330           ms/op
ClientPb.listUser                       sample  228800   4.192 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.071           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.227           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
