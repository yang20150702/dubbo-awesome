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
# Warmup Iteration   1: 2.085 ops/ms
# Warmup Iteration   2: 5.421 ops/ms
# Warmup Iteration   3: 8.510 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 9.203 ops/ms
Iteration   3: 9.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.232 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (9.148, 9.232, 9.346), stdev = 0.102
  CI (99.9%): [7.370, 11.095] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ops/ms
# Warmup Iteration   2: 8.762 ops/ms
# Warmup Iteration   3: 9.578 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.748 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.608 ±(99.9%) 2.876 ops/ms [Average]
  (min, avg, max) = (9.437, 9.608, 9.748), stdev = 0.158
  CI (99.9%): [6.732, 12.485] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 8.427 ops/ms
# Warmup Iteration   3: 9.177 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 9.183 ops/ms
Iteration   3: 9.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.369 ±(99.9%) 4.275 ops/ms [Average]
  (min, avg, max) = (9.183, 9.369, 9.632), stdev = 0.234
  CI (99.9%): [5.095, 13.644] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.048 ops/ms
# Warmup Iteration   2: 6.863 ops/ms
# Warmup Iteration   3: 7.663 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.735 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.820 ±(99.9%) 1.572 ops/ms [Average]
  (min, avg, max) = (7.735, 7.820, 7.907), stdev = 0.086
  CI (99.9%): [6.248, 9.392] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.810 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.007 ms/op
Iteration   1: 3.577 ±(99.9%) 0.006 ms/op
Iteration   2: 3.520 ±(99.9%) 0.009 ms/op
Iteration   3: 3.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.558 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.520, 3.558, 3.578), stdev = 0.033
  CI (99.9%): [2.957, 4.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.349 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
Iteration   1: 3.357 ±(99.9%) 0.004 ms/op
Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
Iteration   3: 3.430 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.352 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (3.268, 3.352, 3.430), stdev = 0.081
  CI (99.9%): [1.877, 4.826] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.242 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.003 ms/op
Iteration   1: 3.461 ±(99.9%) 0.003 ms/op
Iteration   2: 3.398 ±(99.9%) 0.006 ms/op
Iteration   3: 3.560 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 1.483 ms/op [Average]
  (min, avg, max) = (3.398, 3.473, 3.560), stdev = 0.081
  CI (99.9%): [1.990, 4.956] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.242 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.008 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
Iteration   2: 3.916 ±(99.9%) 0.013 ms/op
Iteration   3: 3.898 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.930 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.898, 3.930, 3.975), stdev = 0.040
  CI (99.9%): [3.194, 4.666] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.092 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
Iteration   1: 3.732 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 22.066 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 3.621 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  22.140 ms/op
                 createUser·p0.9999: 25.936 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 3.607 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 31.855 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 262804
  mean =      3.652 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5125 
    [ 2.500,  5.000) = 241795 
    [ 5.000,  7.500) = 13590 
    [ 7.500, 10.000) = 1867 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     18.959 ms/op
     p(99.9900) =     30.128 ms/op
     p(99.9990) =     32.248 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.033 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  12.335 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  21.463 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  19.269 ms/op
                 existUser·p0.9999: 29.681 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287319
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13234 
    [ 2.500,  5.000) = 267421 
    [ 5.000,  7.500) = 5235 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 162 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     19.334 ms/op
     p(99.9900) =     28.653 ms/op
     p(99.9990) =     30.679 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.664 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.010 ms/op
Iteration   1: 3.467 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   5.032 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  19.816 ms/op
                 getUser·p0.9999: 22.668 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.477 ms/op
                 getUser·p0.999:  21.682 ms/op
                 getUser·p0.9999: 28.803 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 3.471 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  19.261 ms/op
                 getUser·p0.9999: 27.814 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276479
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9334 
    [ 2.500,  5.000) = 256285 
    [ 5.000,  7.500) = 8911 
    [ 7.500, 10.000) = 1376 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     19.481 ms/op
     p(99.9900) =     27.614 ms/op
     p(99.9990) =     29.965 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.689 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.012 ms/op
Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  17.365 ms/op
                 listUser·p0.9999: 25.743 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 3.970 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 15.859 ms/op
                 listUser·p1.00:   16.548 ms/op

Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 20.291 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234950
  mean =      4.082 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 224277 
    [ 5.000,  7.500) = 7704 
    [ 7.500, 10.000) = 1962 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     15.058 ms/op
     p(99.9900) =     23.987 ms/op
     p(99.9990) =     26.596 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.232 ± 1.862  ops/ms
ClientPb.existUser                       thrpt       3   9.608 ± 2.876  ops/ms
ClientPb.getUser                         thrpt       3   9.369 ± 4.275  ops/ms
ClientPb.listUser                        thrpt       3   7.820 ± 1.572  ops/ms
ClientPb.createUser                       avgt       3   3.558 ± 0.602   ms/op
ClientPb.existUser                        avgt       3   3.352 ± 1.474   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 1.483   ms/op
ClientPb.listUser                         avgt       3   3.930 ± 0.736   ms/op
ClientPb.createUser                     sample  262804   3.652 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.752           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.324           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.959           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.128           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  287319   3.339 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.276           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.334           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.653           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.736           ms/op
ClientPb.getUser                        sample  276479   3.470 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.914           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.614           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  234950   4.082 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.058           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.987           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
