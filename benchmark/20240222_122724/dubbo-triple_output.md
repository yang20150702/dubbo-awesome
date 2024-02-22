# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.498 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.543 ops/ms
Iteration   1: 12.795 ops/ms
Iteration   2: 12.943 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.890 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (12.795, 12.890, 12.943), stdev = 0.082
  CI (99.9%): [11.398, 14.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.428 ops/ms
# Warmup Iteration   2: 13.163 ops/ms
# Warmup Iteration   3: 13.090 ops/ms
Iteration   1: 13.171 ops/ms
Iteration   2: 13.189 ops/ms
Iteration   3: 13.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.154 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (13.101, 13.154, 13.189), stdev = 0.046
  CI (99.9%): [12.306, 14.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.821 ops/ms
# Warmup Iteration   2: 12.580 ops/ms
# Warmup Iteration   3: 12.727 ops/ms
Iteration   1: 13.091 ops/ms
Iteration   2: 12.836 ops/ms
Iteration   3: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.824 ±(99.9%) 4.977 ops/ms [Average]
  (min, avg, max) = (12.546, 12.824, 13.091), stdev = 0.273
  CI (99.9%): [7.847, 17.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ops/ms
# Warmup Iteration   2: 10.453 ops/ms
# Warmup Iteration   3: 10.820 ops/ms
Iteration   1: 10.827 ops/ms
Iteration   2: 10.779 ops/ms
Iteration   3: 10.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.824 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (10.779, 10.824, 10.865), stdev = 0.043
  CI (99.9%): [10.041, 11.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.465 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.458, 2.465, 2.477), stdev = 0.010
  CI (99.9%): [2.281, 2.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.003 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
Iteration   3: 2.461 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.437, 2.452, 2.461), stdev = 0.013
  CI (99.9%): [2.222, 2.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.003 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.439 ±(99.9%) 0.003 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (2.439, 2.458, 2.476), stdev = 0.019
  CI (99.9%): [2.117, 2.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.007, 3.016, 3.031), stdev = 0.013
  CI (99.9%): [2.774, 3.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.607 ms/op
                 createUser·p0.999:  5.732 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  10.412 ms/op
                 createUser·p0.9999: 12.272 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 11.259 ms/op
                 createUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383474
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187166 
    [ 2.500,  3.750) = 192680 
    [ 3.750,  5.000) = 2806 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 150 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     13.102 ms/op
     p(99.9990) =     14.068 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.939 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  6.518 ms/op
                 existUser·p0.9999: 13.056 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 11.417 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395002
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 198517 
    [ 2.500,  3.750) = 193839 
    [ 3.750,  5.000) = 1900 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     13.148 ms/op
     p(99.9990) =     14.306 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  6.539 ms/op
                 getUser·p0.9999: 14.107 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.967 ms/op
                 getUser·p0.9999: 12.261 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.527 ms/op
                 getUser·p0.999:  5.848 ms/op
                 getUser·p0.9999: 11.709 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387449
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 194283 
    [ 2.500,  3.750) = 187812 
    [ 3.750,  5.000) = 4111 
    [ 5.000,  6.250) = 758 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.467 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.324 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.800 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.953 ms/op
                 listUser·p0.9999: 12.162 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.691 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.305 ms/op
                 listUser·p0.9999: 11.588 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.280 ms/op
                 listUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321614
  mean =      2.982 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 96429 
    [ 2.500,  3.750) = 187447 
    [ 3.750,  5.000) = 30863 
    [ 5.000,  6.250) = 5595 
    [ 6.250,  7.500) = 542 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.644 ms/op
     p(99.9990) =     12.448 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.890 ± 1.492  ops/ms
ClientPb.existUser                       thrpt       3  13.154 ± 0.848  ops/ms
ClientPb.getUser                         thrpt       3  12.824 ± 4.977  ops/ms
ClientPb.listUser                        thrpt       3  10.824 ± 0.782  ops/ms
ClientPb.createUser                       avgt       3   2.465 ± 0.184   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.230   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.342   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.242   ms/op
ClientPb.createUser                     sample  383474   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.952           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.536           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.102           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  395002   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.854           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.438           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.148           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  387449   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.734           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.467           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  321614   2.982 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.691           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.644           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
