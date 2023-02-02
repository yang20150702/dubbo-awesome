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
# Warmup Iteration   1: 1.004 ops/ms
# Warmup Iteration   2: 2.120 ops/ms
# Warmup Iteration   3: 4.825 ops/ms
Iteration   1: 5.173 ops/ms
Iteration   2: 5.679 ops/ms
Iteration   3: 5.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.493 ±(99.9%) 5.076 ops/ms [Average]
  (min, avg, max) = (5.173, 5.493, 5.679), stdev = 0.278
  CI (99.9%): [0.417, 10.569] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.554 ops/ms
# Warmup Iteration   2: 4.256 ops/ms
# Warmup Iteration   3: 5.767 ops/ms
Iteration   1: 6.063 ops/ms
Iteration   2: 6.237 ops/ms
Iteration   3: 6.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.109 ±(99.9%) 2.052 ops/ms [Average]
  (min, avg, max) = (6.027, 6.109, 6.237), stdev = 0.112
  CI (99.9%): [4.057, 8.161] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.591 ops/ms
# Warmup Iteration   2: 4.588 ops/ms
# Warmup Iteration   3: 5.782 ops/ms
Iteration   1: 5.697 ops/ms
Iteration   2: 5.931 ops/ms
Iteration   3: 5.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.829 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (5.697, 5.829, 5.931), stdev = 0.120
  CI (99.9%): [3.640, 8.017] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.475 ops/ms
# Warmup Iteration   2: 3.766 ops/ms
# Warmup Iteration   3: 4.857 ops/ms
Iteration   1: 4.867 ops/ms
Iteration   2: 4.996 ops/ms
Iteration   3: 4.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.941 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (4.867, 4.941, 4.996), stdev = 0.067
  CI (99.9%): [3.727, 6.156] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 17.888 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 6.619 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.773 ±(99.9%) 0.014 ms/op
Iteration   1: 5.350 ±(99.9%) 0.016 ms/op
Iteration   2: 5.433 ±(99.9%) 0.013 ms/op
Iteration   3: 5.575 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.453 ±(99.9%) 2.073 ms/op [Average]
  (min, avg, max) = (5.350, 5.453, 5.575), stdev = 0.114
  CI (99.9%): [3.380, 7.526] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.517 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.496 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.653 ±(99.9%) 0.007 ms/op
Iteration   1: 5.516 ±(99.9%) 0.010 ms/op
Iteration   2: 5.350 ±(99.9%) 0.013 ms/op
Iteration   3: 5.470 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.446 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (5.350, 5.446, 5.516), stdev = 0.086
  CI (99.9%): [3.884, 7.007] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.388 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.660 ±(99.9%) 0.011 ms/op
Iteration   1: 5.776 ±(99.9%) 0.010 ms/op
Iteration   2: 5.614 ±(99.9%) 0.011 ms/op
Iteration   3: 5.433 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.607 ±(99.9%) 3.129 ms/op [Average]
  (min, avg, max) = (5.433, 5.607, 5.776), stdev = 0.172
  CI (99.9%): [2.478, 8.737] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.244 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 7.737 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.563 ±(99.9%) 0.008 ms/op
Iteration   1: 6.466 ±(99.9%) 0.012 ms/op
Iteration   2: 6.512 ±(99.9%) 0.009 ms/op
Iteration   3: 6.627 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.535 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (6.466, 6.535, 6.627), stdev = 0.083
  CI (99.9%): [5.016, 8.054] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.787 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 7.407 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.927 ±(99.9%) 0.028 ms/op
Iteration   1: 5.831 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   9.011 ms/op
                 createUser·p0.99:   12.599 ms/op
                 createUser·p0.999:  32.882 ms/op
                 createUser·p0.9999: 35.392 ms/op
                 createUser·p1.00:   35.652 ms/op

Iteration   2: 5.726 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.176 ms/op
                 createUser·p0.95:   8.421 ms/op
                 createUser·p0.99:   12.501 ms/op
                 createUser·p0.999:  28.213 ms/op
                 createUser·p0.9999: 41.184 ms/op
                 createUser·p1.00:   41.484 ms/op

Iteration   3: 5.747 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.154 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.545 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  28.836 ms/op
                 createUser·p0.9999: 32.309 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166459
  mean =      5.768 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 54795 
    [ 5.000, 10.000) = 107505 
    [10.000, 15.000) = 3404 
    [15.000, 20.000) = 508 
    [20.000, 25.000) = 58 
    [25.000, 30.000) = 50 
    [30.000, 35.000) = 115 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     28.919 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     41.484 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.419 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.662 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.024 ms/op
Iteration   1: 5.559 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.548 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   7.102 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   11.780 ms/op
                 existUser·p0.999:  16.817 ms/op
                 existUser·p0.9999: 28.123 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 5.432 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.898 ms/op
                 existUser·p0.95:   8.233 ms/op
                 existUser·p0.99:   11.551 ms/op
                 existUser·p0.999:  26.280 ms/op
                 existUser·p0.9999: 31.710 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   3: 5.483 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   8.217 ms/op
                 existUser·p0.99:   12.005 ms/op
                 existUser·p0.999:  31.633 ms/op
                 existUser·p0.9999: 36.045 ms/op
                 existUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174625
  mean =      5.491 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 71581 
    [ 5.000,  7.500) = 89910 
    [ 7.500, 10.000) = 9582 
    [10.000, 12.500) = 2235 
    [12.500, 15.000) = 835 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     20.984 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.694 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 7.168 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.785 ±(99.9%) 0.023 ms/op
Iteration   1: 5.899 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   7.733 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   14.451 ms/op
                 getUser·p0.999:  26.306 ms/op
                 getUser·p0.9999: 32.768 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   2: 5.570 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   8.004 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  23.626 ms/op
                 getUser·p0.9999: 33.047 ms/op
                 getUser·p1.00:   33.489 ms/op

Iteration   3: 5.555 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.894 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.542 ms/op
                 getUser·p0.999:  28.432 ms/op
                 getUser·p0.9999: 32.153 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169155
  mean =      5.670 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 62052 
    [ 5.000,  7.500) = 92686 
    [ 7.500, 10.000) = 10017 
    [10.000, 12.500) = 2647 
    [12.500, 15.000) = 945 
    [15.000, 17.500) = 422 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.679 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     32.640 ms/op
     p(99.9990) =     33.398 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.998 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 7.663 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.602 ±(99.9%) 0.028 ms/op
Iteration   1: 6.720 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.215 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   10.519 ms/op
                 listUser·p0.99:   13.664 ms/op
                 listUser·p0.999:  25.756 ms/op
                 listUser·p0.9999: 29.515 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   2: 6.496 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   13.386 ms/op
                 listUser·p0.999:  27.722 ms/op
                 listUser·p0.9999: 31.724 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   3: 6.631 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   8.176 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   13.107 ms/op
                 listUser·p0.999:  27.820 ms/op
                 listUser·p0.9999: 32.061 ms/op
                 listUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145129
  mean =      6.614 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 4556 
    [ 5.000,  7.500) = 118335 
    [ 7.500, 10.000) = 15435 
    [10.000, 12.500) = 4638 
    [12.500, 15.000) = 1281 
    [15.000, 17.500) = 363 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 125 
    [27.500, 30.000) = 101 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      8.307 ms/op
     p(95.0000) =      9.880 ms/op
     p(99.0000) =     13.435 ms/op
     p(99.9000) =     27.034 ms/op
     p(99.9900) =     31.342 ms/op
     p(99.9990) =     35.622 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.493 ± 5.076  ops/ms
ClientPb.existUser                       thrpt       3   6.109 ± 2.052  ops/ms
ClientPb.getUser                         thrpt       3   5.829 ± 2.189  ops/ms
ClientPb.listUser                        thrpt       3   4.941 ± 1.215  ops/ms
ClientPb.createUser                       avgt       3   5.453 ± 2.073   ms/op
ClientPb.existUser                        avgt       3   5.446 ± 1.562   ms/op
ClientPb.getUser                          avgt       3   5.607 ± 3.129   ms/op
ClientPb.listUser                         avgt       3   6.535 ± 1.519   ms/op
ClientPb.createUser                     sample  166459   5.768 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.154           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.569           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.075           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.919           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.652           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.484           ms/op
ClientPb.existUser                      sample  174625   5.491 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.413           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.307           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.780           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.984           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.062           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.635           ms/op
ClientPb.getUser                        sample  169155   5.670 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.583           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.247           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.489           ms/op
ClientPb.listUser                       sample  145129   6.614 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.307           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.435           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.034           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.342           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
