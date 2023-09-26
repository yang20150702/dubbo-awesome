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
# Warmup Iteration   1: 1.949 ops/ms
# Warmup Iteration   2: 5.001 ops/ms
# Warmup Iteration   3: 8.723 ops/ms
Iteration   1: 9.258 ops/ms
Iteration   2: 9.200 ops/ms
Iteration   3: 9.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.335 ±(99.9%) 3.391 ops/ms [Average]
  (min, avg, max) = (9.200, 9.335, 9.547), stdev = 0.186
  CI (99.9%): [5.944, 12.726] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.738 ops/ms
# Warmup Iteration   2: 8.839 ops/ms
# Warmup Iteration   3: 9.702 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.916 ops/ms
Iteration   3: 9.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.692 ±(99.9%) 4.526 ops/ms [Average]
  (min, avg, max) = (9.425, 9.692, 9.916), stdev = 0.248
  CI (99.9%): [5.165, 14.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.138 ops/ms
# Warmup Iteration   2: 8.564 ops/ms
# Warmup Iteration   3: 9.056 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 9.244 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.363 ±(99.9%) 2.243 ops/ms [Average]
  (min, avg, max) = (9.244, 9.363, 9.490), stdev = 0.123
  CI (99.9%): [7.121, 11.606] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ops/ms
# Warmup Iteration   2: 7.257 ops/ms
# Warmup Iteration   3: 7.352 ops/ms
Iteration   1: 7.613 ops/ms
Iteration   2: 7.726 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.711 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (7.613, 7.711, 7.792), stdev = 0.090
  CI (99.9%): [6.061, 9.360] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.604 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.003 ms/op
Iteration   1: 3.523 ±(99.9%) 0.009 ms/op
Iteration   2: 3.488 ±(99.9%) 0.004 ms/op
Iteration   3: 3.423 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.478 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.423, 3.478, 3.523), stdev = 0.051
  CI (99.9%): [2.552, 4.404] (assumes normal distribution)


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
# Warmup Iteration   1: 8.342 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.003 ms/op
Iteration   1: 3.389 ±(99.9%) 0.005 ms/op
Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
Iteration   3: 3.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.294, 3.359, 3.395), stdev = 0.056
  CI (99.9%): [2.329, 4.390] (assumes normal distribution)


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
# Warmup Iteration   1: 8.593 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.002 ms/op
Iteration   1: 3.483 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.003 ms/op
Iteration   3: 3.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.489 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.465, 3.489, 3.520), stdev = 0.028
  CI (99.9%): [2.970, 4.008] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.395 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.004 ms/op
Iteration   1: 4.162 ±(99.9%) 0.009 ms/op
Iteration   2: 4.183 ±(99.9%) 0.007 ms/op
Iteration   3: 4.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.132 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (4.052, 4.132, 4.183), stdev = 0.070
  CI (99.9%): [2.850, 5.415] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.754 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.017 ms/op
Iteration   1: 3.494 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  21.496 ms/op
                 createUser·p0.9999: 23.948 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  22.367 ms/op
                 createUser·p0.9999: 26.631 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.583 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.943 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  25.614 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272432
  mean =      3.524 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6586 
    [ 2.500,  5.000) = 257204 
    [ 5.000,  7.500) = 7176 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     22.104 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     28.551 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.700 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
Iteration   1: 3.263 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.249 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  11.021 ms/op
                 existUser·p0.9999: 23.403 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.381 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  22.341 ms/op
                 existUser·p0.9999: 25.823 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.628 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  20.251 ms/op
                 existUser·p0.9999: 27.086 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286780
  mean =      3.349 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9636 
    [ 2.500,  5.000) = 271250 
    [ 5.000,  7.500) = 4719 
    [ 7.500, 10.000) = 708 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     26.487 ms/op
     p(99.9990) =     27.759 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.304 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.012 ms/op
Iteration   1: 3.601 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.376 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  13.764 ms/op
                 getUser·p0.9999: 24.456 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   2: 3.513 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.882 ms/op
                 getUser·p0.999:  22.905 ms/op
                 getUser·p0.9999: 25.556 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.470 ms/op
                 getUser·p0.999:  19.234 ms/op
                 getUser·p0.9999: 27.224 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270894
  mean =      3.542 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2531 
    [ 2.500,  5.000) = 258643 
    [ 5.000,  7.500) = 8503 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     16.740 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     28.684 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 11.642 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.011 ms/op
Iteration   1: 4.184 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  20.170 ms/op
                 listUser·p0.9999: 23.277 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.162 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.731 ms/op
                 listUser·p0.9999: 17.781 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 4.191 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229612
  mean =      4.179 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 221360 
    [ 5.000,  7.500) = 6261 
    [ 7.500, 10.000) = 1234 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     22.611 ms/op
     p(99.9990) =     23.967 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.335 ± 3.391  ops/ms
ClientPb.existUser                       thrpt       3   9.692 ± 4.526  ops/ms
ClientPb.getUser                         thrpt       3   9.363 ± 2.243  ops/ms
ClientPb.listUser                        thrpt       3   7.711 ± 1.649  ops/ms
ClientPb.createUser                       avgt       3   3.478 ± 0.926   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 1.031   ms/op
ClientPb.getUser                          avgt       3   3.489 ± 0.519   ms/op
ClientPb.listUser                         avgt       3   4.132 ± 1.283   ms/op
ClientPb.createUser                     sample  272432   3.524 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.104           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.984           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  286780   3.349 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.249           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.487           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.820           ms/op
ClientPb.getUser                        sample  270894   3.542 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.376           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.758           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.740           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.608           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  229612   4.179 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.909           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.611           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
