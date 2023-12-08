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
# Warmup Iteration   1: 5.344 ops/ms
# Warmup Iteration   2: 11.963 ops/ms
# Warmup Iteration   3: 12.041 ops/ms
Iteration   1: 12.395 ops/ms
Iteration   2: 12.634 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.605 ±(99.9%) 3.589 ops/ms [Average]
  (min, avg, max) = (12.395, 12.605, 12.785), stdev = 0.197
  CI (99.9%): [9.016, 16.194] (assumes normal distribution)


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
# Warmup Iteration   1: 7.933 ops/ms
# Warmup Iteration   2: 12.996 ops/ms
# Warmup Iteration   3: 12.859 ops/ms
Iteration   1: 12.827 ops/ms
Iteration   2: 12.899 ops/ms
Iteration   3: 12.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.860 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (12.827, 12.860, 12.899), stdev = 0.036
  CI (99.9%): [12.196, 13.525] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 12.521 ops/ms
# Warmup Iteration   3: 12.683 ops/ms
Iteration   1: 12.799 ops/ms
Iteration   2: 12.584 ops/ms
Iteration   3: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.702 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (12.584, 12.702, 12.799), stdev = 0.109
  CI (99.9%): [10.717, 14.687] (assumes normal distribution)


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
# Warmup Iteration   1: 6.893 ops/ms
# Warmup Iteration   2: 10.430 ops/ms
# Warmup Iteration   3: 10.481 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.611 ±(99.9%) 1.300 ops/ms [Average]
  (min, avg, max) = (10.529, 10.611, 10.656), stdev = 0.071
  CI (99.9%): [9.311, 11.911] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
Iteration   3: 2.536 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.500, 2.513, 2.536), stdev = 0.020
  CI (99.9%): [2.149, 2.877] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.428, 2.439, 2.447), stdev = 0.010
  CI (99.9%): [2.262, 2.615] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.003 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
Iteration   2: 2.483 ±(99.9%) 0.003 ms/op
Iteration   3: 2.499 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.474, 2.486, 2.499), stdev = 0.013
  CI (99.9%): [2.254, 2.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
Iteration   3: 3.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.007, 3.015, 3.026), stdev = 0.010
  CI (99.9%): [2.842, 3.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.710 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.544 ms/op
                 createUser·p0.9999: 13.180 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 10.620 ms/op
                 createUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375688
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 178373 
    [ 2.500,  3.750) = 191878 
    [ 3.750,  5.000) = 4530 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.262 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  4.817 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.909 ms/op
                 existUser·p0.9999: 13.837 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  7.894 ms/op
                 existUser·p0.9999: 10.666 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393054
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 197671 
    [ 2.500,  3.750) = 191891 
    [ 3.750,  5.000) = 2649 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.667 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.346 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 14.209 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 12.653 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  8.747 ms/op
                 getUser·p0.9999: 11.405 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382200
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 188689 
    [ 2.500,  3.750) = 187629 
    [ 3.750,  5.000) = 4199 
    [ 5.000,  6.250) = 1149 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      8.834 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.658 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.627 ms/op
                 listUser·p0.9999: 11.098 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.619 ms/op
                 listUser·p0.9999: 10.756 ms/op
                 listUser·p1.00:   11.207 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.460 ms/op
                 listUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315734
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 87226 
    [ 2.500,  3.750) = 187398 
    [ 3.750,  5.000) = 33223 
    [ 5.000,  6.250) = 6426 
    [ 6.250,  7.500) = 668 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.740 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.605 ± 3.589  ops/ms
ClientPb.existUser                       thrpt       3  12.860 ± 0.664  ops/ms
ClientPb.getUser                         thrpt       3  12.702 ± 1.985  ops/ms
ClientPb.listUser                        thrpt       3  10.611 ± 1.300  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.364   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.176   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.232   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.173   ms/op
ClientPb.createUser                     sample  375688   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.757           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  393054   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.667           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.664           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  382200   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.690           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.834           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.434           ms/op
ClientPb.listUser                       sample  315734   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.910           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.321           ms/op
