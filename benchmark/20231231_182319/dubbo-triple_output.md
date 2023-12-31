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
# Warmup Iteration   1: 5.062 ops/ms
# Warmup Iteration   2: 12.289 ops/ms
# Warmup Iteration   3: 12.427 ops/ms
Iteration   1: 12.826 ops/ms
Iteration   2: 12.643 ops/ms
Iteration   3: 12.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.788 ±(99.9%) 2.373 ops/ms [Average]
  (min, avg, max) = (12.643, 12.788, 12.895), stdev = 0.130
  CI (99.9%): [10.414, 15.161] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.136 ops/ms
# Warmup Iteration   2: 13.206 ops/ms
# Warmup Iteration   3: 13.324 ops/ms
Iteration   1: 13.299 ops/ms
Iteration   2: 13.343 ops/ms
Iteration   3: 13.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.351 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (13.299, 13.351, 13.413), stdev = 0.057
  CI (99.9%): [12.305, 14.398] (assumes normal distribution)


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
# Warmup Iteration   1: 7.891 ops/ms
# Warmup Iteration   2: 12.697 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 12.862 ops/ms
Iteration   2: 12.994 ops/ms
Iteration   3: 13.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.955 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (12.862, 12.955, 13.007), stdev = 0.080
  CI (99.9%): [11.490, 14.419] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.075 ops/ms
# Warmup Iteration   2: 10.710 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.756 ops/ms
Iteration   2: 10.871 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.804 ±(99.9%) 1.085 ops/ms [Average]
  (min, avg, max) = (10.756, 10.804, 10.871), stdev = 0.059
  CI (99.9%): [9.719, 11.889] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.468 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.458, 2.468, 2.476), stdev = 0.009
  CI (99.9%): [2.303, 2.632] (assumes normal distribution)


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.439, 2.446, 2.452), stdev = 0.007
  CI (99.9%): [2.319, 2.573] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (2.459, 2.462, 2.463), stdev = 0.002
  CI (99.9%): [2.421, 2.503] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.504 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.004 ms/op
Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
Iteration   3: 2.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.957, 2.964, 2.976), stdev = 0.010
  CI (99.9%): [2.773, 3.155] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  11.396 ms/op
                 createUser·p0.9999: 13.475 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.839 ms/op
                 createUser·p0.999:  7.748 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  8.156 ms/op
                 createUser·p0.9999: 10.532 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386106
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 187383 
    [ 2.500,  3.750) = 194352 
    [ 3.750,  5.000) = 3438 
    [ 5.000,  6.250) = 398 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 146 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.205 ms/op
     p(99.9900) =     12.922 ms/op
     p(99.9990) =     13.929 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  4.979 ms/op
                 existUser·p0.9999: 13.661 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  8.759 ms/op
                 existUser·p0.9999: 12.892 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  7.817 ms/op
                 existUser·p0.9999: 12.122 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393576
  mean =      2.437 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 197839 
    [ 2.500,  3.750) = 192962 
    [ 3.750,  5.000) = 2089 
    [ 5.000,  6.250) = 221 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     12.921 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 12.631 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.200 ms/op
                 getUser·p0.9999: 11.772 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379271
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 187015 
    [ 2.500,  3.750) = 187231 
    [ 3.750,  5.000) = 3823 
    [ 5.000,  6.250) = 736 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.234 ms/op
     p(99.9900) =     13.158 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.585 ms/op
                 listUser·p0.9999: 10.469 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.685 ms/op
                 listUser·p1.00:   13.894 ms/op

Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.408 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321520
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 97368 
    [ 2.500,  3.750) = 186899 
    [ 3.750,  5.000) = 30214 
    [ 5.000,  6.250) = 5592 
    [ 6.250,  7.500) = 702 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.314 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.154 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


# Run complete. Total time: 00:12:56

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.788 ± 2.373  ops/ms
ClientPb.existUser                       thrpt       3  13.351 ± 1.047  ops/ms
ClientPb.getUser                         thrpt       3  12.955 ± 1.465  ops/ms
ClientPb.listUser                        thrpt       3  10.804 ± 1.085  ops/ms
ClientPb.createUser                       avgt       3   2.468 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.127   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.041   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.191   ms/op
ClientPb.createUser                     sample  386106   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.963           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.205           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.922           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.090           ms/op
ClientPb.existUser                      sample  393576   2.437 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.921           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.008           ms/op
ClientPb.getUser                        sample  379271   2.529 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.158           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.877           ms/op
ClientPb.listUser                       sample  321520   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.314           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.894           ms/op
