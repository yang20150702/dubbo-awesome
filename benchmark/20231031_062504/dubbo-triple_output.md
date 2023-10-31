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
# Warmup Iteration   1: 2.042 ops/ms
# Warmup Iteration   2: 5.953 ops/ms
# Warmup Iteration   3: 8.717 ops/ms
Iteration   1: 9.101 ops/ms
Iteration   2: 9.194 ops/ms
Iteration   3: 9.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.234 ±(99.9%) 2.854 ops/ms [Average]
  (min, avg, max) = (9.101, 9.234, 9.406), stdev = 0.156
  CI (99.9%): [6.380, 12.087] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 9.106 ops/ms
Iteration   1: 9.326 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 9.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.539 ±(99.9%) 3.455 ops/ms [Average]
  (min, avg, max) = (9.326, 9.539, 9.689), stdev = 0.189
  CI (99.9%): [6.084, 12.994] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 7.713 ops/ms
# Warmup Iteration   3: 8.713 ops/ms
Iteration   1: 8.787 ops/ms
Iteration   2: 9.091 ops/ms
Iteration   3: 9.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.979 ±(99.9%) 3.037 ops/ms [Average]
  (min, avg, max) = (8.787, 8.979, 9.091), stdev = 0.166
  CI (99.9%): [5.941, 12.016] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.671 ops/ms
# Warmup Iteration   2: 6.980 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.645 ops/ms
Iteration   2: 7.687 ops/ms
Iteration   3: 7.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.660 ±(99.9%) 0.432 ops/ms [Average]
  (min, avg, max) = (7.645, 7.660, 7.687), stdev = 0.024
  CI (99.9%): [7.228, 8.092] (assumes normal distribution)


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
# Warmup Iteration   1: 10.144 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.004 ms/op
Iteration   1: 3.605 ±(99.9%) 0.003 ms/op
Iteration   2: 3.591 ±(99.9%) 0.005 ms/op
Iteration   3: 3.609 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.602 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (3.591, 3.602, 3.609), stdev = 0.009
  CI (99.9%): [3.432, 3.772] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.704 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.004 ms/op
Iteration   1: 3.432 ±(99.9%) 0.003 ms/op
Iteration   2: 3.385 ±(99.9%) 0.004 ms/op
Iteration   3: 3.314 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.377 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.314, 3.377, 3.432), stdev = 0.060
  CI (99.9%): [2.289, 4.466] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.868 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.002 ms/op
Iteration   1: 3.555 ±(99.9%) 0.003 ms/op
Iteration   2: 3.445 ±(99.9%) 0.007 ms/op
Iteration   3: 3.465 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.488 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.445, 3.488, 3.555), stdev = 0.059
  CI (99.9%): [2.414, 4.563] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.568 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.009 ms/op
Iteration   1: 4.215 ±(99.9%) 0.006 ms/op
Iteration   2: 4.180 ±(99.9%) 0.004 ms/op
Iteration   3: 4.109 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.168 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (4.109, 4.168, 4.215), stdev = 0.054
  CI (99.9%): [3.186, 5.150] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.224 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
Iteration   1: 3.512 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  10.775 ms/op
                 createUser·p0.9999: 21.092 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.543 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 23.132 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  22.407 ms/op
                 createUser·p0.9999: 27.321 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272419
  mean =      3.521 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2030 
    [ 2.500,  5.000) = 264916 
    [ 5.000,  7.500) = 4685 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     25.813 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.878 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.007 ms/op
Iteration   1: 3.347 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 22.804 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  22.047 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  18.296 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281235
  mean =      3.410 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7325 
    [ 2.500,  5.000) = 269348 
    [ 5.000,  7.500) = 3701 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     18.539 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.522 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.418 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.010 ms/op
Iteration   1: 3.693 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  18.711 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.551 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  19.661 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.609 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  17.838 ms/op
                 getUser·p0.9999: 25.933 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265370
  mean =      3.617 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2802 
    [ 2.500,  5.000) = 254092 
    [ 5.000,  7.500) = 7013 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     18.555 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     27.253 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.972 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.486 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.014 ms/op
Iteration   1: 4.316 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.633 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  20.227 ms/op
                 listUser·p0.9999: 24.843 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.195 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 16.053 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 4.103 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 16.110 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228517
  mean =      4.203 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 219392 
    [ 5.000,  7.500) = 7193 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     15.343 ms/op
     p(99.9900) =     24.146 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.234 ± 2.854  ops/ms
ClientPb.existUser                       thrpt       3   9.539 ± 3.455  ops/ms
ClientPb.getUser                         thrpt       3   8.979 ± 3.037  ops/ms
ClientPb.listUser                        thrpt       3   7.660 ± 0.432  ops/ms
ClientPb.createUser                       avgt       3   3.602 ± 0.170   ms/op
ClientPb.existUser                        avgt       3   3.377 ± 1.089   ms/op
ClientPb.getUser                          avgt       3   3.488 ± 1.074   ms/op
ClientPb.listUser                         avgt       3   4.168 ± 0.982   ms/op
ClientPb.createUser                     sample  272419   3.521 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.415           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  281235   3.410 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.178           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.539           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.231           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  265370   3.617 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.042           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.555           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.642           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  228517   4.203 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.633           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.343           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.146           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.149           ms/op
