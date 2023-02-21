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
# Warmup Iteration   1: 2.561 ops/ms
# Warmup Iteration   2: 5.834 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 10.046 ops/ms
Iteration   2: 10.062 ops/ms
Iteration   3: 9.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.921 ±(99.9%) 4.218 ops/ms [Average]
  (min, avg, max) = (9.654, 9.921, 10.062), stdev = 0.231
  CI (99.9%): [5.702, 14.139] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ops/ms
# Warmup Iteration   2: 9.162 ops/ms
# Warmup Iteration   3: 10.166 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 10.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.223 ±(99.9%) 4.317 ops/ms [Average]
  (min, avg, max) = (10.074, 10.223, 10.496), stdev = 0.237
  CI (99.9%): [5.906, 14.540] (assumes normal distribution)


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
# Warmup Iteration   1: 3.364 ops/ms
# Warmup Iteration   2: 9.274 ops/ms
# Warmup Iteration   3: 9.894 ops/ms
Iteration   1: 10.206 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.293 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (10.206, 10.293, 10.412), stdev = 0.107
  CI (99.9%): [8.342, 12.243] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.275 ops/ms
# Warmup Iteration   2: 8.099 ops/ms
# Warmup Iteration   3: 8.570 ops/ms
Iteration   1: 8.568 ops/ms
Iteration   2: 8.423 ops/ms
Iteration   3: 8.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.611 ±(99.9%) 3.885 ops/ms [Average]
  (min, avg, max) = (8.423, 8.611, 8.843), stdev = 0.213
  CI (99.9%): [4.726, 12.496] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.242 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.003 ms/op
Iteration   1: 3.182 ±(99.9%) 0.005 ms/op
Iteration   2: 3.216 ±(99.9%) 0.003 ms/op
Iteration   3: 3.124 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.174 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (3.124, 3.174, 3.216), stdev = 0.047
  CI (99.9%): [2.324, 4.023] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.365 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.001 ms/op
Iteration   1: 3.049 ±(99.9%) 0.004 ms/op
Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
Iteration   3: 3.033 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.024 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (2.990, 3.024, 3.049), stdev = 0.030
  CI (99.9%): [2.469, 3.579] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.500 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.007 ms/op
Iteration   1: 3.339 ±(99.9%) 0.005 ms/op
Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
Iteration   3: 3.150 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.231 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (3.150, 3.231, 3.339), stdev = 0.097
  CI (99.9%): [1.456, 5.007] (assumes normal distribution)


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
# Warmup Iteration   1: 8.796 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.007 ms/op
Iteration   1: 3.757 ±(99.9%) 0.011 ms/op
Iteration   2: 3.821 ±(99.9%) 0.003 ms/op
Iteration   3: 3.770 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.782 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.757, 3.782, 3.821), stdev = 0.034
  CI (99.9%): [3.165, 4.400] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.338 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.009 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  11.321 ms/op
                 createUser·p0.9999: 19.993 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  9.166 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  15.232 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301826
  mean =      3.180 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19574 
    [ 2.500,  5.000) = 276763 
    [ 5.000,  7.500) = 4606 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     20.998 ms/op
     p(99.9990) =     21.888 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 7.440 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  12.905 ms/op
                 existUser·p0.9999: 19.776 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  16.302 ms/op
                 existUser·p0.9999: 21.586 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  13.836 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311524
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20814 
    [ 2.500,  5.000) = 286602 
    [ 5.000,  7.500) = 3342 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 6.984 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
Iteration   1: 3.196 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  12.119 ms/op
                 getUser·p0.9999: 18.546 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.488 ms/op
                 getUser·p0.999:  9.003 ms/op
                 getUser·p0.9999: 21.950 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  13.238 ms/op
                 getUser·p0.9999: 21.171 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301408
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19501 
    [ 2.500,  5.000) = 274814 
    [ 5.000,  7.500) = 6052 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 173 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 9.591 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.011 ms/op
Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  16.091 ms/op
                 listUser·p0.9999: 20.136 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 16.863 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.668 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.116 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.661 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256439
  mean =      3.743 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 247179 
    [ 5.000,  7.500) = 7165 
    [ 7.500, 10.000) = 1378 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 383 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.739 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.123 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.921 ± 4.218  ops/ms
ClientPb.existUser                       thrpt       3  10.223 ± 4.317  ops/ms
ClientPb.getUser                         thrpt       3  10.293 ± 1.950  ops/ms
ClientPb.listUser                        thrpt       3   8.611 ± 3.885  ops/ms
ClientPb.createUser                       avgt       3   3.174 ± 0.850   ms/op
ClientPb.existUser                        avgt       3   3.024 ± 0.555   ms/op
ClientPb.getUser                          avgt       3   3.231 ± 1.775   ms/op
ClientPb.listUser                         avgt       3   3.782 ± 0.617   ms/op
ClientPb.createUser                     sample  301826   3.180 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.991           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.998           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.020           ms/op
ClientPb.existUser                      sample  311524   3.078 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.905           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.647           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.987           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.429           ms/op
ClientPb.getUser                        sample  301408   3.183 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.059           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.332           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.872           ms/op
ClientPb.listUser                       sample  256439   3.743 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.343           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.739           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.053           ms/op
