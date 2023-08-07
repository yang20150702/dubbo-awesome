# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.042 ops/ms
# Warmup Iteration   2: 2.351 ops/ms
# Warmup Iteration   3: 5.000 ops/ms
Iteration   1: 5.560 ops/ms
Iteration   2: 5.473 ops/ms
Iteration   3: 5.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.565 ±(99.9%) 1.734 ops/ms [Average]
  (min, avg, max) = (5.473, 5.565, 5.663), stdev = 0.095
  CI (99.9%): [3.831, 7.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.689 ops/ms
# Warmup Iteration   2: 4.531 ops/ms
# Warmup Iteration   3: 5.797 ops/ms
Iteration   1: 5.639 ops/ms
Iteration   2: 5.509 ops/ms
Iteration   3: 5.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.597 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (5.509, 5.597, 5.642), stdev = 0.076
  CI (99.9%): [4.216, 6.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 4.164 ops/ms
# Warmup Iteration   3: 5.423 ops/ms
Iteration   1: 5.428 ops/ms
Iteration   2: 5.534 ops/ms
Iteration   3: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.560 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (5.428, 5.560, 5.717), stdev = 0.146
  CI (99.9%): [2.890, 8.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.440 ops/ms
# Warmup Iteration   2: 3.581 ops/ms
# Warmup Iteration   3: 4.393 ops/ms
Iteration   1: 4.441 ops/ms
Iteration   2: 4.664 ops/ms
Iteration   3: 4.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.635 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (4.441, 4.635, 4.800), stdev = 0.181
  CI (99.9%): [1.325, 7.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.509 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.756 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.907 ±(99.9%) 0.010 ms/op
Iteration   1: 5.739 ±(99.9%) 0.011 ms/op
Iteration   2: 5.919 ±(99.9%) 0.017 ms/op
Iteration   3: 5.818 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.825 ±(99.9%) 1.652 ms/op [Average]
  (min, avg, max) = (5.739, 5.825, 5.919), stdev = 0.091
  CI (99.9%): [4.173, 7.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.195 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 7.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.773 ±(99.9%) 0.012 ms/op
Iteration   1: 5.720 ±(99.9%) 0.014 ms/op
Iteration   2: 6.072 ±(99.9%) 0.007 ms/op
Iteration   3: 5.673 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.822 ±(99.9%) 3.975 ms/op [Average]
  (min, avg, max) = (5.673, 5.822, 6.072), stdev = 0.218
  CI (99.9%): [1.847, 9.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.173 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.537 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.784 ±(99.9%) 0.010 ms/op
Iteration   1: 5.814 ±(99.9%) 0.008 ms/op
Iteration   2: 6.078 ±(99.9%) 0.010 ms/op
Iteration   3: 5.785 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.892 ±(99.9%) 2.951 ms/op [Average]
  (min, avg, max) = (5.785, 5.892, 6.078), stdev = 0.162
  CI (99.9%): [2.941, 8.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.773 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 8.702 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.745 ±(99.9%) 0.016 ms/op
Iteration   1: 7.592 ±(99.9%) 0.010 ms/op
Iteration   2: 7.250 ±(99.9%) 0.018 ms/op
Iteration   3: 7.512 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.451 ±(99.9%) 3.258 ms/op [Average]
  (min, avg, max) = (7.250, 7.451, 7.592), stdev = 0.179
  CI (99.9%): [4.193, 10.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 22.810 ±(99.9%) 0.393 ms/op
# Warmup Iteration   2: 8.659 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 7.438 ±(99.9%) 0.046 ms/op
Iteration   1: 6.499 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.988 ms/op
                 createUser·p0.90:   8.684 ms/op
                 createUser·p0.95:   10.289 ms/op
                 createUser·p0.99:   13.746 ms/op
                 createUser·p0.999:  27.442 ms/op
                 createUser·p0.9999: 31.755 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   2: 6.154 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.841 ms/op
                 createUser·p0.90:   7.774 ms/op
                 createUser·p0.95:   8.815 ms/op
                 createUser·p0.99:   11.993 ms/op
                 createUser·p0.999:  26.834 ms/op
                 createUser·p0.9999: 38.572 ms/op
                 createUser·p1.00:   39.059 ms/op

Iteration   3: 6.296 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.716 ms/op
                 createUser·p0.50:   5.882 ms/op
                 createUser·p0.90:   7.922 ms/op
                 createUser·p0.95:   9.585 ms/op
                 createUser·p0.99:   13.631 ms/op
                 createUser·p0.999:  21.189 ms/op
                 createUser·p0.9999: 41.277 ms/op
                 createUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 152087
  mean =      6.313 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 21589 
    [ 5.000, 10.000) = 124322 
    [10.000, 15.000) = 5318 
    [15.000, 20.000) = 613 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 99 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 47 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      8.102 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     13.206 ms/op
     p(99.9000) =     26.801 ms/op
     p(99.9900) =     39.032 ms/op
     p(99.9990) =     41.667 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.430 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.934 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 5.766 ±(99.9%) 0.023 ms/op
Iteration   1: 5.755 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.507 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   7.447 ms/op
                 existUser·p0.95:   8.716 ms/op
                 existUser·p0.99:   11.616 ms/op
                 existUser·p0.999:  15.361 ms/op
                 existUser·p0.9999: 32.979 ms/op
                 existUser·p1.00:   36.241 ms/op

Iteration   2: 5.702 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.736 ms/op
                 existUser·p0.50:   5.358 ms/op
                 existUser·p0.90:   7.201 ms/op
                 existUser·p0.95:   8.290 ms/op
                 existUser·p0.99:   11.329 ms/op
                 existUser·p0.999:  25.781 ms/op
                 existUser·p0.9999: 31.914 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   3: 5.587 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   8.389 ms/op
                 existUser·p0.99:   11.715 ms/op
                 existUser·p0.999:  30.827 ms/op
                 existUser·p0.9999: 35.145 ms/op
                 existUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169012
  mean =      5.681 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 55885 
    [ 5.000,  7.500) = 98833 
    [ 7.500, 10.000) = 10886 
    [10.000, 12.500) = 2260 
    [12.500, 15.000) = 751 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.355 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     37.089 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.436 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.966 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.077 ±(99.9%) 0.027 ms/op
Iteration   1: 5.963 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.556 ms/op
                 getUser·p0.50:   5.620 ms/op
                 getUser·p0.90:   7.430 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.993 ms/op
                 getUser·p0.999:  16.573 ms/op
                 getUser·p0.9999: 28.175 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 6.201 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   5.693 ms/op
                 getUser·p0.90:   8.069 ms/op
                 getUser·p0.95:   10.043 ms/op
                 getUser·p0.99:   14.369 ms/op
                 getUser·p0.999:  27.784 ms/op
                 getUser·p0.9999: 34.778 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   3: 5.721 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.578 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   11.338 ms/op
                 getUser·p0.999:  26.284 ms/op
                 getUser·p0.9999: 29.682 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 161113
  mean =      5.955 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 38831 
    [ 5.000,  7.500) = 104755 
    [ 7.500, 10.000) = 12318 
    [10.000, 12.500) = 3575 
    [12.500, 15.000) = 946 
    [15.000, 17.500) = 301 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.517 ms/op
     p(99.9000) =     26.272 ms/op
     p(99.9900) =     33.664 ms/op
     p(99.9990) =     35.113 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.399 ±(99.9%) 0.391 ms/op
# Warmup Iteration   2: 8.241 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 7.011 ±(99.9%) 0.031 ms/op
Iteration   1: 7.073 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   3.097 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   9.388 ms/op
                 listUser·p0.95:   10.650 ms/op
                 listUser·p0.99:   14.246 ms/op
                 listUser·p0.999:  31.383 ms/op
                 listUser·p0.9999: 35.673 ms/op
                 listUser·p1.00:   40.239 ms/op

Iteration   2: 6.684 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.875 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   13.206 ms/op
                 listUser·p0.999:  29.691 ms/op
                 listUser·p0.9999: 32.232 ms/op
                 listUser·p1.00:   32.965 ms/op

Iteration   3: 6.745 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.875 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.644 ms/op
                 listUser·p0.999:  34.389 ms/op
                 listUser·p0.9999: 38.766 ms/op
                 listUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140564
  mean =      6.830 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4747 
    [ 5.000, 10.000) = 127887 
    [10.000, 15.000) = 7075 
    [15.000, 20.000) = 484 
    [20.000, 25.000) = 93 
    [25.000, 30.000) = 122 
    [30.000, 35.000) = 113 
    [35.000, 40.000) = 42 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.875 ms/op
     p(50.0000) =      6.349 ms/op
     p(90.0000) =      8.798 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     30.671 ms/op
     p(99.9900) =     37.942 ms/op
     p(99.9990) =     40.106 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.565 ± 1.734  ops/ms
ClientPb.existUser                       thrpt       3   5.597 ± 1.381  ops/ms
ClientPb.getUser                         thrpt       3   5.560 ± 2.670  ops/ms
ClientPb.listUser                        thrpt       3   4.635 ± 3.310  ops/ms
ClientPb.createUser                       avgt       3   5.825 ± 1.652   ms/op
ClientPb.existUser                        avgt       3   5.822 ± 3.975   ms/op
ClientPb.getUser                          avgt       3   5.892 ± 2.951   ms/op
ClientPb.listUser                         avgt       3   7.451 ± 3.258   ms/op
ClientPb.createUser                     sample  152087   6.313 ± 0.016   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.90    sample           8.102           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.535           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.206           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.801           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.009           ms/op
ClientPb.existUser                      sample  169012   5.681 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.355           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.471           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.551           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.224           ms/op
ClientPb.getUser                        sample  161113   5.955 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.180           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.077           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.517           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.272           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.664           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  140564   6.830 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.875           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.779           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.671           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.942           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.239           ms/op
