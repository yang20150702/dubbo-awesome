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
# Warmup Iteration   1: 4.888 ops/ms
# Warmup Iteration   2: 12.162 ops/ms
# Warmup Iteration   3: 12.453 ops/ms
Iteration   1: 12.767 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.770 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (12.725, 12.770, 12.818), stdev = 0.047
  CI (99.9%): [11.920, 13.620] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.318 ops/ms
# Warmup Iteration   2: 13.125 ops/ms
# Warmup Iteration   3: 12.999 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.341 ops/ms
Iteration   3: 13.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.222 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (13.135, 13.222, 13.341), stdev = 0.107
  CI (99.9%): [11.269, 15.174] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.849 ops/ms
# Warmup Iteration   2: 12.628 ops/ms
# Warmup Iteration   3: 12.833 ops/ms
Iteration   1: 12.896 ops/ms
Iteration   2: 12.813 ops/ms
Iteration   3: 12.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.886 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (12.813, 12.886, 12.948), stdev = 0.068
  CI (99.9%): [11.645, 14.126] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.221 ops/ms
# Warmup Iteration   2: 10.576 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.613 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (10.576, 10.613, 10.653), stdev = 0.039
  CI (99.9%): [9.911, 11.316] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.492, 2.506, 2.517), stdev = 0.013
  CI (99.9%): [2.269, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.415 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.415, 2.432, 2.450), stdev = 0.018
  CI (99.9%): [2.108, 2.756] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.471, 2.487, 2.507), stdev = 0.018
  CI (99.9%): [2.155, 2.820] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.545 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
Iteration   3: 2.996 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.959, 2.978, 2.996), stdev = 0.018
  CI (99.9%): [2.643, 3.312] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.119 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.490 ms/op
                 createUser·p0.9999: 12.111 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  8.309 ms/op
                 createUser·p0.9999: 10.379 ms/op
                 createUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383595
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 185424 
    [ 2.500,  3.750) = 193834 
    [ 3.750,  5.000) = 3400 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.641 ms/op
     p(99.9900) =     13.063 ms/op
     p(99.9990) =     13.984 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 16.663 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  7.188 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  7.725 ms/op
                 existUser·p0.9999: 12.433 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387921
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 192894 
    [ 2.500,  3.750) = 190670 
    [ 3.750,  5.000) = 3328 
    [ 5.000,  6.250) = 532 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      7.374 ms/op
     p(99.9900) =     13.625 ms/op
     p(99.9990) =     17.107 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  7.431 ms/op
                 getUser·p0.9999: 13.686 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  9.622 ms/op
                 getUser·p0.9999: 13.819 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  7.747 ms/op
                 getUser·p0.9999: 11.230 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385367
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 191887 
    [ 2.500,  3.750) = 187592 
    [ 3.750,  5.000) = 4274 
    [ 5.000,  6.250) = 1047 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     13.548 ms/op
     p(99.9990) =     14.275 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.740 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.677 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.808 ms/op
                 listUser·p0.9999: 11.187 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.738 ms/op
                 listUser·p0.9999: 11.890 ms/op
                 listUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319351
  mean =      3.003 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 94031 
    [ 2.500,  3.750) = 185804 
    [ 3.750,  5.000) = 32155 
    [ 5.000,  6.250) = 5894 
    [ 6.250,  7.500) = 685 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 206 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.442 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.770 ± 0.850  ops/ms
ClientPb.existUser                       thrpt       3  13.222 ± 1.952  ops/ms
ClientPb.getUser                         thrpt       3  12.886 ± 1.241  ops/ms
ClientPb.listUser                        thrpt       3  10.613 ± 0.703  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.237   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.324   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.333   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.335   ms/op
ClientPb.createUser                     sample  383595   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.641           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.063           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  387921   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.374           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.625           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.022           ms/op
ClientPb.getUser                        sample  385367   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.743           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.060           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.548           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  319351   3.003 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.485           ms/op
