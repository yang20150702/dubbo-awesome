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
# Warmup Iteration   1: 0.951 ops/ms
# Warmup Iteration   2: 2.142 ops/ms
# Warmup Iteration   3: 4.102 ops/ms
Iteration   1: 5.182 ops/ms
Iteration   2: 5.288 ops/ms
Iteration   3: 5.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.335 ±(99.9%) 3.313 ops/ms [Average]
  (min, avg, max) = (5.182, 5.335, 5.536), stdev = 0.182
  CI (99.9%): [2.022, 8.648] (assumes normal distribution)


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
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 4.486 ops/ms
# Warmup Iteration   3: 5.777 ops/ms
Iteration   1: 5.739 ops/ms
Iteration   2: 5.844 ops/ms
Iteration   3: 5.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.845 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (5.739, 5.845, 5.952), stdev = 0.107
  CI (99.9%): [3.896, 7.793] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.447 ops/ms
# Warmup Iteration   2: 4.168 ops/ms
# Warmup Iteration   3: 5.073 ops/ms
Iteration   1: 5.152 ops/ms
Iteration   2: 5.668 ops/ms
Iteration   3: 5.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.446 ±(99.9%) 4.844 ops/ms [Average]
  (min, avg, max) = (5.152, 5.446, 5.668), stdev = 0.266
  CI (99.9%): [0.602, 10.291] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.528 ops/ms
# Warmup Iteration   2: 3.904 ops/ms
# Warmup Iteration   3: 4.542 ops/ms
Iteration   1: 4.610 ops/ms
Iteration   2: 4.797 ops/ms
Iteration   3: 4.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.734 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (4.610, 4.734, 4.797), stdev = 0.108
  CI (99.9%): [2.768, 6.700] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.298 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.938 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.131 ±(99.9%) 0.008 ms/op
Iteration   1: 5.752 ±(99.9%) 0.008 ms/op
Iteration   2: 5.866 ±(99.9%) 0.011 ms/op
Iteration   3: 5.701 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.773 ±(99.9%) 1.534 ms/op [Average]
  (min, avg, max) = (5.701, 5.773, 5.866), stdev = 0.084
  CI (99.9%): [4.239, 7.307] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 19.737 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.742 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.820 ±(99.9%) 0.005 ms/op
Iteration   1: 5.642 ±(99.9%) 0.012 ms/op
Iteration   2: 5.526 ±(99.9%) 0.014 ms/op
Iteration   3: 5.693 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.621 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (5.526, 5.621, 5.693), stdev = 0.086
  CI (99.9%): [4.055, 7.186] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.284 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 8.118 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.956 ±(99.9%) 0.013 ms/op
Iteration   1: 5.917 ±(99.9%) 0.007 ms/op
Iteration   2: 5.874 ±(99.9%) 0.012 ms/op
Iteration   3: 5.702 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.831 ±(99.9%) 2.080 ms/op [Average]
  (min, avg, max) = (5.702, 5.831, 5.917), stdev = 0.114
  CI (99.9%): [3.751, 7.911] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 22.765 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 8.469 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.032 ±(99.9%) 0.018 ms/op
Iteration   1: 6.819 ±(99.9%) 0.010 ms/op
Iteration   2: 6.673 ±(99.9%) 0.011 ms/op
Iteration   3: 6.843 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.779 ±(99.9%) 1.677 ms/op [Average]
  (min, avg, max) = (6.673, 6.779, 6.843), stdev = 0.092
  CI (99.9%): [5.102, 8.456] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.996 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 7.229 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.961 ±(99.9%) 0.041 ms/op
Iteration   1: 5.814 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.527 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.847 ms/op
                 createUser·p0.99:   12.452 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 32.506 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   2: 5.674 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.589 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   7.882 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  28.656 ms/op
                 createUser·p0.9999: 33.109 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   3: 6.082 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.954 ms/op
                 createUser·p0.95:   9.175 ms/op
                 createUser·p0.99:   12.911 ms/op
                 createUser·p0.999:  29.702 ms/op
                 createUser·p0.9999: 32.530 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164061
  mean =      5.852 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 43727 
    [ 5.000,  7.500) = 104070 
    [ 7.500, 10.000) = 12128 
    [10.000, 12.500) = 2582 
    [12.500, 15.000) = 995 
    [15.000, 17.500) = 295 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 90 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     12.354 ms/op
     p(99.9000) =     24.965 ms/op
     p(99.9900) =     32.656 ms/op
     p(99.9990) =     36.551 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.070 ±(99.9%) 0.365 ms/op
# Warmup Iteration   2: 6.731 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.751 ±(99.9%) 0.023 ms/op
Iteration   1: 5.671 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.079 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   7.168 ms/op
                 existUser·p0.95:   8.454 ms/op
                 existUser·p0.99:   11.469 ms/op
                 existUser·p0.999:  15.712 ms/op
                 existUser·p0.9999: 25.341 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 5.446 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.089 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.709 ms/op
                 existUser·p0.95:   7.692 ms/op
                 existUser·p0.99:   11.171 ms/op
                 existUser·p0.999:  22.717 ms/op
                 existUser·p0.9999: 25.928 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 5.569 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.048 ms/op
                 existUser·p0.95:   8.372 ms/op
                 existUser·p0.99:   12.354 ms/op
                 existUser·p0.999:  25.070 ms/op
                 existUser·p0.9999: 30.220 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172572
  mean =      5.561 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 66362 
    [ 5.000,  7.500) = 93623 
    [ 7.500, 10.000) = 9070 
    [10.000, 12.500) = 2228 
    [12.500, 15.000) = 813 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.079 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.176 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     31.145 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 16.967 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 7.389 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.887 ±(99.9%) 0.026 ms/op
Iteration   1: 6.086 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.548 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   8.339 ms/op
                 getUser·p0.95:   9.830 ms/op
                 getUser·p0.99:   13.656 ms/op
                 getUser·p0.999:  24.052 ms/op
                 getUser·p0.9999: 29.900 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   2: 5.732 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.781 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   12.075 ms/op
                 getUser·p0.999:  28.706 ms/op
                 getUser·p0.9999: 41.380 ms/op
                 getUser·p1.00:   41.615 ms/op

Iteration   3: 5.872 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.355 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.324 ms/op
                 getUser·p0.95:   8.552 ms/op
                 getUser·p0.99:   12.440 ms/op
                 getUser·p0.999:  32.779 ms/op
                 getUser·p0.9999: 46.399 ms/op
                 getUser·p1.00:   47.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162966
  mean =      5.893 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45183 
    [ 5.000, 10.000) = 112193 
    [10.000, 15.000) = 4802 
    [15.000, 20.000) = 504 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 118 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 36 

  Percentiles, ms/op:
      p(0.0000) =      2.355 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      9.093 ms/op
     p(99.0000) =     12.861 ms/op
     p(99.9000) =     27.560 ms/op
     p(99.9900) =     45.385 ms/op
     p(99.9990) =     46.815 ms/op
     p(99.9999) =     47.186 ms/op
    p(100.0000) =     47.186 ms/op


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
# Warmup Iteration   1: 20.795 ±(99.9%) 0.383 ms/op
# Warmup Iteration   2: 8.839 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 7.194 ±(99.9%) 0.036 ms/op
Iteration   1: 6.876 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   14.573 ms/op
                 listUser·p0.999:  29.196 ms/op
                 listUser·p0.9999: 31.850 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 6.707 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   8.684 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.142 ms/op
                 listUser·p0.999:  30.547 ms/op
                 listUser·p0.9999: 33.529 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   3: 6.693 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.232 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   10.224 ms/op
                 listUser·p0.99:   14.926 ms/op
                 listUser·p0.999:  31.693 ms/op
                 listUser·p0.9999: 34.814 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142139
  mean =      6.758 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 3834 
    [ 5.000,  7.500) = 111528 
    [ 7.500, 10.000) = 19026 
    [10.000, 12.500) = 5295 
    [12.500, 15.000) = 1302 
    [15.000, 17.500) = 600 
    [17.500, 20.000) = 191 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 89 
    [32.500, 35.000) = 53 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      8.716 ms/op
     p(95.0000) =     10.207 ms/op
     p(99.0000) =     14.215 ms/op
     p(99.9000) =     30.048 ms/op
     p(99.9900) =     34.350 ms/op
     p(99.9990) =     35.958 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.335 ± 3.313  ops/ms
ClientPb.existUser                       thrpt       3   5.845 ± 1.949  ops/ms
ClientPb.getUser                         thrpt       3   5.446 ± 4.844  ops/ms
ClientPb.listUser                        thrpt       3   4.734 ± 1.966  ops/ms
ClientPb.createUser                       avgt       3   5.773 ± 1.534   ms/op
ClientPb.existUser                        avgt       3   5.621 ± 1.566   ms/op
ClientPb.getUser                          avgt       3   5.831 ± 2.080   ms/op
ClientPb.listUser                         avgt       3   6.779 ± 1.677   ms/op
ClientPb.createUser                     sample  164061   5.852 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.487           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.684           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.354           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.965           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.656           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  172572   5.561 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.176           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.747           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.775           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.098           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.359           ms/op
ClientPb.getUser                        sample  162966   5.893 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.355           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.093           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.861           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          45.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.186           ms/op
ClientPb.listUser                       sample  142139   6.758 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.224           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.207           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.215           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.048           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.350           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
