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
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 5.392 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.662 ops/ms
Iteration   2: 9.476 ops/ms
Iteration   3: 9.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.456 ±(99.9%) 3.942 ops/ms [Average]
  (min, avg, max) = (9.231, 9.456, 9.662), stdev = 0.216
  CI (99.9%): [5.514, 13.398] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ops/ms
# Warmup Iteration   2: 8.880 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 9.618 ops/ms
Iteration   2: 9.690 ops/ms
Iteration   3: 9.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.719 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (9.618, 9.719, 9.848), stdev = 0.118
  CI (99.9%): [7.574, 11.864] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.088 ops/ms
# Warmup Iteration   2: 8.858 ops/ms
# Warmup Iteration   3: 9.252 ops/ms
Iteration   1: 8.926 ops/ms
Iteration   2: 9.469 ops/ms
Iteration   3: 9.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.161 ±(99.9%) 5.086 ops/ms [Average]
  (min, avg, max) = (8.926, 9.161, 9.469), stdev = 0.279
  CI (99.9%): [4.074, 14.247] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.436 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 7.884 ops/ms
Iteration   1: 7.960 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.084 ±(99.9%) 1.974 ops/ms [Average]
  (min, avg, max) = (7.960, 8.084, 8.160), stdev = 0.108
  CI (99.9%): [6.110, 10.057] (assumes normal distribution)


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
# Warmup Iteration   1: 10.099 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.004 ms/op
Iteration   1: 3.361 ±(99.9%) 0.007 ms/op
Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
Iteration   3: 3.368 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.391 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.361, 3.391, 3.442), stdev = 0.045
  CI (99.9%): [2.571, 4.211] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.385 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.007 ms/op
Iteration   1: 3.358 ±(99.9%) 0.014 ms/op
Iteration   2: 3.258 ±(99.9%) 0.010 ms/op
Iteration   3: 3.239 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.285 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.239, 3.285, 3.358), stdev = 0.064
  CI (99.9%): [2.119, 4.452] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.987 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.008 ms/op
Iteration   1: 3.380 ±(99.9%) 0.005 ms/op
Iteration   2: 3.429 ±(99.9%) 0.002 ms/op
Iteration   3: 3.471 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.380, 3.427, 3.471), stdev = 0.045
  CI (99.9%): [2.599, 4.254] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.645 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.009 ms/op
Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
Iteration   2: 3.907 ±(99.9%) 0.012 ms/op
Iteration   3: 3.815 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.887 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (3.815, 3.887, 3.937), stdev = 0.064
  CI (99.9%): [2.725, 5.048] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.995 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.011 ms/op
Iteration   1: 3.418 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  22.262 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 3.390 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.392 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  23.586 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  20.799 ms/op
                 createUser·p0.9999: 27.861 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280383
  mean =      3.423 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10266 
    [ 2.500,  5.000) = 262877 
    [ 5.000,  7.500) = 6321 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 123 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     21.138 ms/op
     p(99.9900) =     27.360 ms/op
     p(99.9990) =     28.351 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.010 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.751 ms/op
                 existUser·p0.9999: 32.547 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   2: 3.244 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.672 ms/op
                 existUser·p0.9999: 33.498 ms/op
                 existUser·p1.00:   43.844 ms/op

Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 29.917 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296583
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 291962 
    [ 5.000, 10.000) = 4313 
    [10.000, 15.000) = 52 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 111 
    [25.000, 30.000) = 90 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     10.942 ms/op
     p(99.9900) =     32.845 ms/op
     p(99.9990) =     34.534 ms/op
     p(99.9999) =     43.844 ms/op
    p(100.0000) =     43.844 ms/op


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
# Warmup Iteration   1: 8.510 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   6.561 ms/op
                 getUser·p0.999:  21.642 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 3.358 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  9.404 ms/op
                 getUser·p0.9999: 28.717 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282765
  mean =      3.392 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4103 
    [ 2.500,  5.000) = 269576 
    [ 5.000,  7.500) = 7950 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     27.835 ms/op
     p(99.9990) =     29.437 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 10.442 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
Iteration   1: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  21.608 ms/op
                 listUser·p0.9999: 27.364 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.132 ms/op
                 listUser·p0.9999: 20.705 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 3.928 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242418
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 234701 
    [ 5.000,  7.500) = 5383 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.377 ms/op
     p(99.9900) =     26.511 ms/op
     p(99.9990) =     27.844 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.456 ± 3.942  ops/ms
ClientPb.existUser                       thrpt       3   9.719 ± 2.145  ops/ms
ClientPb.getUser                         thrpt       3   9.161 ± 5.086  ops/ms
ClientPb.listUser                        thrpt       3   8.084 ± 1.974  ops/ms
ClientPb.createUser                       avgt       3   3.391 ± 0.820   ms/op
ClientPb.existUser                        avgt       3   3.285 ± 1.167   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 0.828   ms/op
ClientPb.listUser                         avgt       3   3.887 ± 1.161   ms/op
ClientPb.createUser                     sample  280383   3.423 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.360           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  296583   3.235 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.845           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.844           ms/op
ClientPb.getUser                        sample  282765   3.392 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.415           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.403           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.835           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  242418   3.961 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.516           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.377           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.511           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
