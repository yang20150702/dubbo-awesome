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
# Warmup Iteration   1: 5.032 ops/ms
# Warmup Iteration   2: 12.055 ops/ms
# Warmup Iteration   3: 12.271 ops/ms
Iteration   1: 12.427 ops/ms
Iteration   2: 12.578 ops/ms
Iteration   3: 12.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.549 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (12.427, 12.549, 12.642), stdev = 0.110
  CI (99.9%): [10.540, 14.558] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.524 ops/ms
# Warmup Iteration   2: 12.961 ops/ms
# Warmup Iteration   3: 12.959 ops/ms
Iteration   1: 13.022 ops/ms
Iteration   2: 12.963 ops/ms
Iteration   3: 12.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.978 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (12.948, 12.978, 13.022), stdev = 0.039
  CI (99.9%): [12.267, 13.689] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.969 ops/ms
# Warmup Iteration   2: 12.404 ops/ms
# Warmup Iteration   3: 12.138 ops/ms
Iteration   1: 12.603 ops/ms
Iteration   2: 12.611 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.570 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (12.497, 12.570, 12.611), stdev = 0.064
  CI (99.9%): [11.407, 13.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.601 ops/ms
# Warmup Iteration   2: 10.358 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.611 ops/ms
Iteration   3: 10.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.539 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (10.468, 10.539, 10.611), stdev = 0.071
  CI (99.9%): [9.238, 11.840] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.572 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.558, 2.572, 2.581), stdev = 0.012
  CI (99.9%): [2.351, 2.793] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.029 ms/op [Average]
  (min, avg, max) = (2.442, 2.444, 2.445), stdev = 0.002
  CI (99.9%): [2.415, 2.472] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.460, 2.469, 2.478), stdev = 0.009
  CI (99.9%): [2.313, 2.626] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.580 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.004 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.026, 3.044, 3.058), stdev = 0.016
  CI (99.9%): [2.752, 3.335] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 13.839 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 12.589 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 11.820 ms/op
                 createUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379477
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 182522 
    [ 2.500,  3.750) = 192792 
    [ 3.750,  5.000) = 3175 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      9.544 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.759 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  6.559 ms/op
                 existUser·p0.9999: 14.237 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.193 ms/op
                 existUser·p0.9999: 13.175 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.837 ms/op
                 existUser·p0.9999: 11.436 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390300
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 192855 
    [ 2.500,  3.750) = 193795 
    [ 3.750,  5.000) = 2847 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      7.387 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     14.700 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.006 ms/op
Iteration   1: 2.551 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  11.839 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  8.490 ms/op
                 getUser·p0.9999: 12.899 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   3: 2.609 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.387 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 10.953 ms/op
                 getUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373549
  mean =      2.568 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 182145 
    [ 2.500,  3.750) = 185219 
    [ 3.750,  5.000) = 4297 
    [ 5.000,  6.250) = 1268 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.098 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.120 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.947 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 10.840 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 10.846 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.638 ms/op
                 listUser·p0.9999: 10.938 ms/op
                 listUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312741
  mean =      3.067 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 82164 
    [ 2.500,  3.750) = 187750 
    [ 3.750,  5.000) = 34974 
    [ 5.000,  6.250) = 6362 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 212 
    [ 8.750, 10.000) = 353 
    [10.000, 11.250) = 191 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     10.879 ms/op
     p(99.9990) =     12.482 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.549 ± 2.009  ops/ms
ClientPb.existUser                       thrpt       3  12.978 ± 0.711  ops/ms
ClientPb.getUser                         thrpt       3  12.570 ± 1.163  ops/ms
ClientPb.listUser                        thrpt       3  10.539 ± 1.301  ops/ms
ClientPb.createUser                       avgt       3   2.572 ± 0.221   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.029   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.157   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.291   ms/op
ClientPb.createUser                     sample  379477   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.544           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.287           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.499           ms/op
ClientPb.existUser                      sample  390300   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.772           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.387           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.631           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  373549   2.568 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.869           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.098           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  312741   3.067 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.879           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.845           ms/op
