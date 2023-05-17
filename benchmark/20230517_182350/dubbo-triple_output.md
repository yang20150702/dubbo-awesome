# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.103 ops/ms
# Warmup Iteration   2: 2.454 ops/ms
# Warmup Iteration   3: 5.107 ops/ms
Iteration   1: 5.263 ops/ms
Iteration   2: 5.128 ops/ms
Iteration   3: 5.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.192 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (5.128, 5.192, 5.263), stdev = 0.068
  CI (99.9%): [3.952, 6.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.435 ops/ms
# Warmup Iteration   2: 4.788 ops/ms
# Warmup Iteration   3: 5.490 ops/ms
Iteration   1: 5.519 ops/ms
Iteration   2: 5.509 ops/ms
Iteration   3: 5.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.545 ±(99.9%) 0.973 ops/ms [Average]
  (min, avg, max) = (5.509, 5.545, 5.606), stdev = 0.053
  CI (99.9%): [4.571, 6.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.545 ops/ms
# Warmup Iteration   2: 4.638 ops/ms
# Warmup Iteration   3: 5.550 ops/ms
Iteration   1: 5.448 ops/ms
Iteration   2: 5.466 ops/ms
Iteration   3: 5.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.520 ±(99.9%) 2.008 ops/ms [Average]
  (min, avg, max) = (5.448, 5.520, 5.647), stdev = 0.110
  CI (99.9%): [3.512, 7.528] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.666 ops/ms
# Warmup Iteration   2: 3.859 ops/ms
# Warmup Iteration   3: 4.641 ops/ms
Iteration   1: 4.816 ops/ms
Iteration   2: 4.876 ops/ms
Iteration   3: 4.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.826 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (4.785, 4.826, 4.876), stdev = 0.046
  CI (99.9%): [3.983, 5.669] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 20.389 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 7.408 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.217 ±(99.9%) 0.012 ms/op
Iteration   1: 6.162 ±(99.9%) 0.019 ms/op
Iteration   2: 5.822 ±(99.9%) 0.009 ms/op
Iteration   3: 5.747 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.910 ±(99.9%) 4.035 ms/op [Average]
  (min, avg, max) = (5.747, 5.910, 6.162), stdev = 0.221
  CI (99.9%): [1.875, 9.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.839 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.636 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.921 ±(99.9%) 0.006 ms/op
Iteration   1: 5.938 ±(99.9%) 0.011 ms/op
Iteration   2: 5.866 ±(99.9%) 0.008 ms/op
Iteration   3: 5.878 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.894 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (5.866, 5.894, 5.938), stdev = 0.039
  CI (99.9%): [5.189, 6.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 19.010 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.794 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.884 ±(99.9%) 0.010 ms/op
Iteration   1: 5.746 ±(99.9%) 0.012 ms/op
Iteration   2: 5.868 ±(99.9%) 0.012 ms/op
Iteration   3: 5.809 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.808 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (5.746, 5.808, 5.868), stdev = 0.061
  CI (99.9%): [4.689, 6.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.387 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 7.326 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.632 ±(99.9%) 0.016 ms/op
Iteration   1: 6.801 ±(99.9%) 0.016 ms/op
Iteration   2: 6.686 ±(99.9%) 0.028 ms/op
Iteration   3: 6.642 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.710 ±(99.9%) 1.503 ms/op [Average]
  (min, avg, max) = (6.642, 6.710, 6.801), stdev = 0.082
  CI (99.9%): [5.207, 8.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.517 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 7.039 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.465 ±(99.9%) 0.033 ms/op
Iteration   1: 6.005 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   5.890 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.094 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  24.663 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   2: 6.138 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.454 ms/op
                 createUser·p0.50:   5.997 ms/op
                 createUser·p0.90:   7.815 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   11.616 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 29.976 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 5.655 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.470 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   7.258 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   11.223 ms/op
                 createUser·p0.999:  29.456 ms/op
                 createUser·p0.9999: 33.217 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161991
  mean =      5.926 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 44678 
    [ 5.000,  7.500) = 100816 
    [ 7.500, 10.000) = 13882 
    [10.000, 12.500) = 1736 
    [12.500, 15.000) = 558 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.433 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     20.521 ms/op
     p(99.9900) =     32.604 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.141 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.309 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.729 ±(99.9%) 0.019 ms/op
Iteration   1: 5.527 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   9.912 ms/op
                 existUser·p0.999:  24.168 ms/op
                 existUser·p0.9999: 30.350 ms/op
                 existUser·p1.00:   32.735 ms/op

Iteration   2: 6.027 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   5.849 ms/op
                 existUser·p0.90:   7.512 ms/op
                 existUser·p0.95:   8.339 ms/op
                 existUser·p0.99:   11.993 ms/op
                 existUser·p0.999:  25.492 ms/op
                 existUser·p0.9999: 29.612 ms/op
                 existUser·p1.00:   30.245 ms/op

Iteration   3: 5.411 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.634 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.685 ms/op
                 existUser·p0.95:   7.356 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  13.808 ms/op
                 existUser·p0.9999: 30.617 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170000
  mean =      5.643 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 57785 
    [ 5.000,  7.500) = 100646 
    [ 7.500, 10.000) = 9590 
    [10.000, 12.500) = 1262 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     32.621 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.287 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.437 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.342 ±(99.9%) 0.027 ms/op
Iteration   1: 5.946 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.396 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.897 ms/op
                 getUser·p0.95:   9.306 ms/op
                 getUser·p0.99:   14.795 ms/op
                 getUser·p0.999:  24.813 ms/op
                 getUser·p0.9999: 32.297 ms/op
                 getUser·p1.00:   32.604 ms/op

Iteration   2: 5.951 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.540 ms/op
                 getUser·p0.50:   5.833 ms/op
                 getUser·p0.90:   7.340 ms/op
                 getUser·p0.95:   8.167 ms/op
                 getUser·p0.99:   9.929 ms/op
                 getUser·p0.999:  27.635 ms/op
                 getUser·p0.9999: 41.673 ms/op
                 getUser·p1.00:   43.188 ms/op

Iteration   3: 5.754 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   5.587 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  27.352 ms/op
                 getUser·p0.9999: 30.882 ms/op
                 getUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163040
  mean =      5.882 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 46425 
    [ 5.000, 10.000) = 113280 
    [10.000, 15.000) = 2673 
    [15.000, 20.000) = 418 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.396 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     26.572 ms/op
     p(99.9900) =     40.219 ms/op
     p(99.9990) =     42.858 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.814 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 7.995 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 7.034 ±(99.9%) 0.035 ms/op
Iteration   1: 6.763 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.757 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   13.291 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 31.985 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   2: 6.858 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   12.117 ms/op
                 listUser·p0.999:  30.696 ms/op
                 listUser·p0.9999: 33.512 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   3: 6.964 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.322 ms/op
                 listUser·p0.50:   6.783 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.762 ms/op
                 listUser·p0.99:   12.861 ms/op
                 listUser·p0.999:  30.507 ms/op
                 listUser·p0.9999: 35.652 ms/op
                 listUser·p1.00:   39.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140005
  mean =      6.861 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 5668 
    [ 5.000,  7.500) = 102724 
    [ 7.500, 10.000) = 26354 
    [10.000, 12.500) = 3663 
    [12.500, 15.000) = 980 
    [15.000, 17.500) = 305 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 80 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.757 ms/op
     p(50.0000) =      6.578 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =      9.552 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     29.164 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     38.837 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.192 ± 1.239  ops/ms
ClientPb.existUser                       thrpt       3   5.545 ± 0.973  ops/ms
ClientPb.getUser                         thrpt       3   5.520 ± 2.008  ops/ms
ClientPb.listUser                        thrpt       3   4.826 ± 0.843  ops/ms
ClientPb.createUser                       avgt       3   5.910 ± 4.035   ms/op
ClientPb.existUser                        avgt       3   5.894 ± 0.705   ms/op
ClientPb.getUser                          avgt       3   5.808 ± 1.119   ms/op
ClientPb.listUser                         avgt       3   6.710 ± 1.503   ms/op
ClientPb.createUser                     sample  161991   5.926 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.433           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.520           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.521           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.604           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  170000   5.643 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.997           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.029           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.848           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.322           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.678           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.048           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  163040   5.882 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.396           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.373           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.503           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.829           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.572           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.219           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.188           ms/op
ClientPb.listUser                       sample  140005   6.861 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.578           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.164           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.144           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.256           ms/op
